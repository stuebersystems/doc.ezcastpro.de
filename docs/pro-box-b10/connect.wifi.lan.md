# Mit WLAN/LAN verbinden

Sie haben die Möglichkeit die EZCast Pro Box II mit Ihrer Netzwerkinfrastruktur entweder drahtlos per WLAN oder per LAN-Kabel zu verbinden.

## Warum soll man EZCast Pro mit WLAN/LAN verbinden?

Es gibt mehrere Gründe, warum Sie die EZCast Pro Box II mit Ihrer Netzwerkinfrastruktur verbinden sollen:

* Sie sind mit der Pro Box II per [Apple AirPlay](airplay.md), [Google Cast](googlecast.md) oder die EZCast Pro [Software bzw. die App](ezcastproapp.md) verbunden und möchten **Inhalte vom Internet** präsentieren.

* Sie möchten die Pro Box II auf die **neueste Firmware-Version** [aktualisieren](firmware-upgrade.md).

* Sie möchten per **Fernzugriff** auf die Funktion [Erweiterte Einstellungen](adv.settings.md) zugreifen, um die EZCast Pro Box II zu verwalten.
  
* **Integriertes Netzwerk**: Wenn alle Ihre Endgeräte und EZCast Pro-Geräte im gleichen Netzwerk sind, entfällt die Notwendigkeit, jedes Mal zur SSID des EZCast Pro zu wechseln, wenn Sie Ihren Bildschirm in einen anderen Raum übertragen möchten.

## Mit WLAN verbinden

!!! tip "Bitte beachten"
    
	Wenn das EZCast Pro Gerät im Standardmodus läuft, empfehlen wir das EZCast Pro Gerät nicht mit einer Dual-Band 2,4Ghz/5Ghz SSID zu verbinden, sondern mit einer dedizierten SSID, die auf das 5Ghz-Band eingeschränkt ist. Wenn das EZCast Pro Gerät im [Legacymodus](adv.settings.md#legacymode) läuft, verbinden Sie das EZCast Pro Gerät mit einer dedizierten 2,4Ghz-Band SSID.

### Voraussetzungen

Bevor Sie die EZCast Pro Box II mit Ihrem WLAN verbinden, prüfen Sie bitte die empfohlenen Voraussetzungen:

* **Access Point unterstützt** WLAN-Standard **802.11ac**.
* **Verbinden Sie nicht mit einer Dual-Band 2,4Ghz/5Ghz SSID**. Nutzen Sie stattdessen eine dedizierte SSID, die auf den [5GHz-Bereich](https://en.wikipedia.org/wiki/List_of_WLAN_channels#5_GHz_(802.11a/h/j/n/ac/ax)) (20Mhz-Kanäle 36,40,44,48) beschränkt ist. Benutzen Sie bitte nicht [DFS-Kanäle](https://en.wikipedia.org/wiki/Dynamic_frequency_selection), um Abbrüche durch plötzlichen Kanalwechsel während der Bildschirmübertragung zu vermeiden. Wenn das EZCast Pro Gerät im [Legacymodus](adv.settings.md#legacymode) läuft, verbinden Sie das EZCast Pro Gerät mit einer dedizierten 2,4Ghz-Band SSID.
* Eine **dedizierte SSID für das EZCast Pro Gerät** z.B. `EZCast_5Ghz` auf **Kanal 48** und im gleichen Netzwerk eine **andere SSID für die Benutzer** bzw. die Endgeräte z.B. `Benutzer_5Ghz` auf **Kanal 40** anlegen, damit die verfügbare WLAN-Kanalbandbreite für das EZCast Pro Gerät mit anderen Clients nicht geteilt werden muss. 
* Halten Sie den Abstand zwischen der EZCast Pro Box II und dem Access Point sowie den Endgeräten auf maximal 30 Meter. Achten Sie dabei auf eine optimale Signalstärke zwischen -40 dBm und -50 dBm. Beim Einrichten bitte die [Signalstärke](wifi.environment.md) prüfen.
* **Access Point liegt im selben Raum** wie die Box. Dies ist für das 5 GHz-Frequenzband besonders wichtig.
* Eine sogenannte **Sichtlinie** von der **Box zum Access Point** sowie von der **Box zu den Endgeräten** mit möglichst wenigen Hindernissen. **Vermeiden Sie Gegenstände direkt neben der EZCast Pro Box II**, die WLAN-Signale schlucken bzw. reflektieren, beispielsweise: Wände, Metallflächen, reflektierende Flächen und andere elektronische Geräte, etc.
* Bei einem **Gast-WLAN** bitte **Client-Isolation deaktivieren** oder eine neue SSID anlegen, die nicht als "Gast-WLAN" eingestellt ist, sondern als "Standard". Standardmäßig verhindert ein Gast-WLAN, dass drahtlose Clients desselben Access-Points miteinander kommunizieren. Dies kann die Funktionalität von Streaming-Protokollen wie AirPlay, Chromecast usw. beeinträchtigen. 

![](/assets/img/setup.wifi.box.png)

Wir empfehlen die Verwendung eines WLAN-Analyzers, um Ihre  [WLAN-Umgebung zu scannen](wifi.environment.md) und eine saubere Frequenznutzung fürs kabellose Präsentieren zu planen.

### Erweiterte Einstellungen öffnen

* Verbinden Sie Ihr Endgerät mit der SSID des EZCast Pro II Gerätes. Die Zugangsdaten werden oben auf der Startseite angezeigt:

![](/assets/img/proII.direct.connect.png)

* In die Adressleiste eines Webbrowsers geben Sie die IP-Adresse des EZCast Pro Gerätes mit der Bezeichnung `Direct Link IP` **192.168.168.1** ein. Die Einstellungsoberfläche des EZCast Pro Gerätes erscheint:

![](/assets/img/proII_directIP.connect.png)

### Sich als Admin anmelden

* Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#hardreset) zurück.

![](/assets/img/EZCastII_Login.png)

### Networkeinstellungen auswählen

* Aus dem Menü oben links wählen Sie `Networkeinstellungen`.

![](/assets/img/ezcastpro.II.select.networkmanagement.png)

* Wählen den Punkt `Mit 5GHz WLAN-Router/AP verbinden` aus.

![](/assets/img/ezcastpro.II.select.connect5ghz.png)

* Verbinden Sie die Pro Box mit Ihrem WLAN-Router.

![](/assets/img/EZCastPro.II.Wifi.Internet.jpg)

!!! tip "Hinweis"

	Bitte beachten Sie: Standardmäßig kann die EZCast Pro Box II nur mit einem 5GHz WLAN-Router verbunden werden. Sie können jedoch den [Legacy-Modus (2,4 GHz WLAN)](adv.settings.md#legacymode) aktivieren. **Bitte nicht mit einer Dual-Band 2,4Ghz/5Ghz SSID verbinden**, sondern mit einer dedizierten SSID, die auf den [2,4GHz-Bereich](https://en.wikipedia.org/wiki/List_of_WLAN_channels#2.4_GHz_(802.11b/g/n/ax)) eingeschränkt ist.

Wenn die EZCast Pro Box II mit Ihrem Netzwerk bzw. Ihrem Router verbunden ist, wird eine von Ihrem Netzwerk vergebenen IP-Adressen mit der Bezeichnung `Infrastructure IP` auf dem Bildschirm angezeigt, wie unten abgebildet:

![](/assets/img/ProDongleII_connected_to_router.png)

!!! info "Hinweis"

    Eine Miracast-Verbindung mit der EZCast Pro Box II wird als zusätzliche WLAN-Verbindung nur zur Übertragung des Bildschirms ausgebaut. Für die Internetinhalte verwendet das Endgerät die bisherige bzw. die zuletzt verbundene WLAN/LAN Internetverbindung oder es nutzt den mobilen Datenzugang eines Providers. Weitere Informationen zu Miracast [finden Sie hier](miracast.md).

## Mit LAN verbinden

Schließen Sie dazu ein Netzwerkkabel in den `ETHERNET` Anschluss an der Rückseite der EZCast Pro Box an und verbinden Sie das Kabel mit Ihrem Netzwerk bzw. mit Ihrem Router.

![](/assets/img/B10_ports.png)

!!! tip "Bitte beachten"
    
	Wenn ein LAN-Kabel an der Box angeschlossen ist, wird der Internetzugang per WLAN automatisch deaktiviert.

* Wenn die EZCast Pro Box II mit Ihrem Netzwerk bzw. Ihrem Router verbunden ist, wird eine von Ihrem Netzwerk vergebenen IP-Adressen mit der Bezeichnung `Infrustructure IP` auf dem Bildschirm angezeigt, wie unten abgebildet:

![](/assets/img/ProDongleII_connected_to_router.png)

!!! info "Hinweis"

    Eine Miracast-Verbindung mit der EZCast Pro Box II wird als zusätzliche WLAN-Verbindung nur zur Übertragung des Bildschirms ausgebaut. Für die Internetinhalte verwendet das Endgerät die bisherige bzw. die zuletzt verbundene WLAN/LAN Internetverbindung oder es nutzt den mobilen Datenzugang eines Providers. Weitere Informationen zu Miracast [finden Sie hier](miracast.md).
	
## Problembehandlung

### Internet-Router-Signalstärke

Die EZCast Pro Box II hat eine Funkreichweite (Sichtlinie) von bis zu 30m. Eine geringe Signalanzeige bezieht sich auf eine schlechte Signalstärke zwischen der Box und Ihrem Router bzw. Ihrem Access-Point. Dies kann zu einer abgehackten Wiedergabe von Videos und Inhalten führen, wenn die Inhalte vom Internet abhängig sind oder wenn Ihre Mobilgeräte mit der Box über Ihre Infrastruktur verbinden.

Dies kann verschiedene Ursachen und somit verschiedene Lösungen haben:

**1. Problem:** Der Abstand zwischen der EZCast Pro Box II und dem Router bzw. Wireless-Access-Point ist zu groß.

Lösung: Versuchen Sie den Abstand zu reduzieren oder installieren Sie einen zusätzlichen Wireless-Access-Point.

**2. Problem:** Es liegen Wände oder andere Gegenstände zwischen der EZCast Pro Box II und dem Router bzw. dem Wireless-Access-Point, welche die Signalstärke verschlechtern.

Lösung: Stellen Sie sicher, dass die EZCast Pro Box II keine Hindernisse zum Router bzw. zum Access-Point hat. Wenn notwendig, installieren Sie einen zusätzlichen Access-Point.

![](/assets/img/ProII.Internet.Signal.png)