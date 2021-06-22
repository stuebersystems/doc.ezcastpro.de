# Von EZCast Pro verwendete Anschlüsse

In den folgenden Tabellen sind die von EZCast Pro verwendeten Anschlüsse aufgeführt. 

## Verwendete Anschlüsse

### AirPlay

Port | Typ                  
:---- | :----------------------
7000 | TCP          
7001 | TCP         
7100 | TCP         
5353 | UDP         

### EZCast Pro App / ProCast

| Port |
| :---- |
| 2425 |
| 63630 |

### ChromeCast

| Port | Typ
| :---- | :---
| 80 | TCP
| 443 | TCP
| 8008 | TCP
| 8009 | TCP
| 53 | UDP
| 1900 | UDP
| 5353 | UDP

### Web-Server für die Web-Oberfläche 

| Port |
| :---- |
| 80 |
| 8080 |

### Over-The-Air Firmware

| Port |
| :---- |
| 80 |
| 443 |

### DLNA

| Port | Typ
| :---- | :---
| 1900 | UDP
| 2869 | TCP


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

Für die Funktion `ChromeCast`:

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

EZCast Pro Gerät -> Router -> Internet NTP Server (d.h. time.google.com) 

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

EZCast Pro Gerät -> Router/DNS (d.h. time.google.com) -> Interner NTP Server -> Internet NTP Server

