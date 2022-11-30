# Von EZCast Pro verwendete Anschlüsse

In den folgenden Tabelle sind die von EZCast Pro verwendeten Anschlüsse aufgeführt. 

## Verwendete Anschlüsse

Port | Typ | Tx / Rx | Beschreibung                
| :---- | :--- | :---- | :---
53 | TCP  | Rx | DNS server    
53 | UDP  | Rx | ChromeCast
67 | UDP  | Tx | DHCP server
68 | UDP  | Rx | DHCP client   
80 | TCP  | TxRx | AirPlay, ChromeCast, Web server, FW OTA
443 | TCP  | TxRx | AirPlay, ChromeCast, FW OTA
554 | TCP  | TxRx | RTSP AirPlay
1900 | UDP  | Rx | ChromeCast / DLNA   
2425 | TCP  | TxRx | TX <-> RX
2869 | TCP  | TxRx | DLNA    
3689 | TCP  | TxRx | AirPlay    
5297 | TCP  | TxRx | Bonjour    
5289 | TCP/UDP  | TxRx | Bonjour
5353 | UDP  | TxRx | Bonjour, AirPlay, ChromeCast 
7000 | TCP  | Rx | AirPlay   
7001 | TCP  | Rx | AirPlay   
7100 | TCP  | Rx | AirPlay  
7236 | TCP  | Rx | RTSP Miracast   
8008 | TCP  | Rx | ChromeCast  
8009 | TCP  | Rx | ChromeCast   
8080 | TCP  | Rx | Web server    
25030 | TCP  | TxRx | Miracast HDCP
49159 | UDP  | TxRx | Bonjour, AirPlay
41963 | UDP  | TxRx | Bonjour, AirPlay
63630 | TCP  | TxRx | TX <-> RX   

## EZCast Pro verwendete Anschlüsse untersuchen

Haben Sie festgestellt, dass bestimmte Funktionen von EZCast Pro über Ihre Infrastruktur nicht funktionieren? Microsoft stellt eine grafische Benutzeroberfläche des Tools namens PortQueryUI bereit, die zur Fehlersuche in solchen Szenarien mit Port-Konnektivitätsproblemen verwendet werden kann. Dieses Tool können Sie zur Behebung von TCP/IP-Verbindungsproblemen verwenden. Das Hilfsprogramm meldet den Portstatus von TCP- und UDP-Ports auf einem Gerät, das Sie auswählen.

### PortQueryUI.exe herunterladen

* Laden Sie das Tool [portqueryui.exe](https://download.microsoft.com/download/3/f/4/3f4c6a54-65f0-4164-bdec-a3411ba24d3a/portqryui.exe) herunter und führen Sie es aus. Zum Akzeptieren der Lizenzvereinbarung klicken Sie auf `Yes`:

![Lizenzvereinbarung akzeptieren](/assets/img/PortQueryUI-License-Agreement.png)

* Extrahieren Sie die Dateien im gewünschten Ordner:

![die Dateien extrahieren](/assets/img/PortQryUI_extract.png)
 
* Die `PortQueryUI.exe` muss nicht installiert werden, sondern kann einfach per Doppelklick gestartet werden:

![PortQueryUI.exe per Doppelklick starten](/assets/img/portqueryui.exe.png)

### Ports abfragen

* Notieren Sie sich die Infrastruktur IP-Adresse, die unten links auf der Startseite angezeigt wird:

![Infrastruktur IP-Adresse notieren](/assets/img/Infrustructure_IPaddress.png)

Im Feld `destination IP` geben Sie die Infrastruktur IP-Adresse ein. Geben Sie anschließend die zu prüfenden Ports an und klicken Sie auf `Query`, wie zum Beispiel:

Für die Funktion [Google Cast]:

* `Ports to query` = **80,443,8008,8009**
* `Protocol` = **TCP**

![Ports angeben](/assets/img/TCP.png)

### Weitere Informationen

PortQueryUI.exe meldet den Status eines TCP/IP-Ports auf eine der folgenden drei Arten:

`LISTENING` - Abhören

Der Port auf dem ausgewählten EZCast Pro Gerät wird von einem Prozess abgehört. PortQueryUI.exe hat eine Antwort vom Port erhalten.

`NOT LISTENING` - Nicht abhören

Der Zielport auf dem EZCast Pro Gerät wird nicht von einem Prozess abgehört. Überprüfen Sie bitte Ihre Infrastruktur, um Netzwerkverbindungen für den Port zu erlauben.

`Filtered`

Der Port auf dem ausgewählten EZCast Pro Gerät wird gefiltert. PortQueryUI.exe hat keine Antwort vom Port erhalten. Ein Prozess hört den Port möglicherweise ab oder nicht. Standardmäßig werden die TCP-Ports dreimal abgefragt, und die UDP-Ports werden einmal abgefragt, bevor ein Bericht angibt, dass der Port gefiltert wird.

![Abfrage Ergebnisse](/assets/img/TCP.results.png)

## NTP (Network Time Protocol) 

Nahezu überall spielt das Datum und die Uhrzeit eine wichtige Rolle. NTP (Network Time Protocol) ist ein Netzwerkprotokoll, mit dem die Uhren von Geräten sich über ein Netzwerk synchronisieren können. Es arbeitet mit einem oder mehreren NTP-Servern, die eine hochpräzise Zeit beibehalten, und erlaubt Clients, diese Zeit abzufragen. Diese Client-Geräte fragen den Server ab und stellen dann automatisch ihre eigene interne Uhr so ein, dass sie den NTP-Server widerspiegelt. EZCast Pro-Geräte versuchen, die folgenden NTP-Server in der unten angegebenen Reihenfolge abzufragen:

EZCast Pro Gerät -> Router -> Internet NTP-Server (d.h. time.google.com) 

````
time.google.com
pool.ntp.org
cn.ntp.org.cn
ntp.ubuntu.com
ntp1.aliyun.com
ntp2.aliyun.com
ntp3.aliyun.com
````

Für Netzwerkinfrastrukturen, die den Geräten keinen direkten Zugriff auf das Internet erlauben, wird ein eigener lokaler Zeitserver eingesetzt. Um die Zeitsynchronisation der EZCast Pro Geräte mit Ihrem NTP-Server zu integrieren, erstellen Sie bitte einen oder mehrere Einträge auf Ihrem DNS-Server, die auf den entsprechenden lokalen NTP-Server verweisen:

EZCast Pro Gerät -> Interner DNS-Server (d.h. time.google.com) -> Interner NTP-Server -> Internet NTP-Server

