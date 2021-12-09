# Internetzugang

## Wozu braucht die EZCast Pro Box II einen Internetzugang?

Für die EZCast Pro Box II wird eine Internet-Verbindung in folgenden Fällen benötigt:

* Sie sind mit der Pro Box II per [Apple AirPlay](airplay.md), [Chromecast](chromecast.md) oder die EZCast Pro [Software bzw. die App](ezcastproapp.md) verbunden und möchten Inhalte vom Internet präsentieren.

* Sie möchten die Pro Box II auf die neueste Firmware-Version [aktualisieren](firmware-upgrade.md).

* Sie möchten per Fernzugriff auf die Funktion [Erweiterte Einstellungen](adv.settings.md) zugreifen, um die EZCast Pro Box II zu verwalten.
  
* Integriertes Netzwerk: Wenn alle Ihre Endgeräte und EZCast Pro-Geräte im gleichen Netzwerk sind, entfällt die Notwendigkeit, jedes Mal zur SSID des EZCast Pro zu wechseln, wenn Sie Ihren Bildschirm in einen anderen Raum übertragen möchten.

!!! info "Hinweis"

    Eine Miracast-Verbindung mit der EZCast Pro Box II wird als zusätzliche WLAN-Verbindung nur zur Übertragung des Bildschirms ausgebaut. Für die Internetinhalte verwendet das Endgerät die bisherige bzw. die zuletzt verbundene WLAN/LAN Internetverbindung oder es nutzt den mobilen Datenzugang eines Providers. Weitere Informationen zu Miracast [finden Sie hier](miracast.md).

## EZCast Pro Box II mit WLAN verbinden

Mit Hilfe der Funktion Erweiterte Einstellungen in der `EZCastPro` Software für [Windows und macOS](quickstart.md#InstallSoftware) oder in der App für [Android und iOS](quickstart.md#InstallApp) können Sie Ihr EZCast Pro Gerät mit Ihrem WLAN vebinden.

### Erweiterte Einstellungen öffnen

* Rufen Sie die App bzw. die Software `EZCastPro` auf Ihrem Gerät auf und wählen Sie die Pro Box II aus der Geräteliste aus.

* Auf Windows/macOS wählen Sie `Erweiterte Einstellungen` unten links:

![](/assets/img/Win-App-Advanced-Settings.png)

* Auf iOS/Android wählen Sie die Schaltfläche `Einstellungen` oben links, anschließend tippen Sie auf `Erweiterte`:

![](/assets/img/iOS_adv-settings.png)

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
    
	Bitte beachten: Standardmäßig kann die EZCast Pro Box II nur mit einem 5GHz WLAN-Router verbunden werden. Sie können jedoch den [Legacy-Modus (2,4 GHz WLAN)](adv.settings.md#legacymode) aktivieren.

* Wenn die EZCast Pro Box II mit Ihrem Netzwerk bzw. Ihrem Router verbunden ist, wird eine von Ihrem Netzwerk vergebenen IP-Adressen mit der Bezeichnung `Infrustructure IP` auf dem Bildschirm angezeigt, wie unten abgebildet:

![](/assets/img/ProDongleII_connected_to_router.png)

## EZCast Pro Box II mit LAN verbinden

Schließen Sie dazu ein Netzwerkkabel in den `ETHERNET` Anschluss an der Rückseite der EZCast Pro Box an und verbinden Sie das Kabel mit Ihrem Netzwerk bzw. mit Ihrem Router.

![](/assets/img/B10_ports.png)

!!! tip "Bitte beachten"
    
	Wenn ein LAN-Kabel an der Box angeschlossen ist, wird der Internetzugang per WLAN automatisch deaktiviert.

* Wenn die EZCast Pro Box II mit Ihrem Netzwerk bzw. Ihrem Router verbunden ist, wird eine von Ihrem Netzwerk vergebenen IP-Adressen mit der Bezeichnung `Infrustructure IP` auf dem Bildschirm angezeigt, wie unten abgebildet:

![](/assets/img/ProDongleII_connected_to_router.png)

## Problembehandlung

### Internet-Router-Signalstärke

Die EZCast Pro Box II hat eine Funkreichweite (Sichtlinie) von bis zu 30m. Eine geringe Signalanzeige bezieht sich auf eine schlechte Signalstärke zwischen der Box und Ihrem Router bzw. Ihrem Access-Point. Dies kann zu einer abgehackten Wiedergabe von Videos und Inhalten führen, wenn die Inhalte vom Internet abhängig sind oder wenn Ihre Mobilgeräte mit dem Stick über Ihre Infrastruktur verbinden.

Dies kann verschiedene Ursachen und somit verschiedene Lösungen haben:

**1. Problem:** Der Abstand zwischen der EZCast Pro Box II und dem Router bzw. Wireless-Access-Point ist zu groß.

Lösung: Versuchen Sie den Abstand zu reduzieren oder installieren Sie einen zusätzlichen Wireless-Access-Point.

**2. Problem:** Es liegen Wände oder andere Gegenstände zwischen der EZCast Pro Box II und dem Router bzw. dem Wireless-Access-Point, welche die Signalstärke verschlechtern.

Lösung: Stellen Sie sicher, dass die EZCast Pro Box II keine Hindernisse zum Router bzw. zum Access-Point hat. Wenn notwendig, installieren Sie einen zusätzlichen Access-Point.

![](/assets/img/ProII.Internet.Signal.png)