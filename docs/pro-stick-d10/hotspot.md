# Mit Hotspot verbinden

Sollte Sie Verbindungsprobleme bzw. Abbrüche mit dem EZCast Gerät über Ihre Infrastruktur haben, bitten wir Sie möglicherweise zu Support-Zwecken, dass Sie Ihr EZCast Pro Gerät mit einem Hotspot verbinden und die Leistung vergleichen. Der Hotspot sollte die Bildschirmübertragung eines Videos mindestens 30 - 60 Minuten ohne Probleme leisten können. Zu diesem Test benötigen Sie folgende Geräte:

* ein Android Handy, ein iPhone 11 oder höher Einen Windows-Notebook, das am Stromnetz angeschlossen ist.

## Hotspot einrichten

!!! tip "Warning" 
	Prüfen Sie vor Testbeginn, ob das Netzgerät am Android bzw. am iOS-Gerät angeschlossen ist, damit der Hotspot sich während des Tests nicht ausschaltet.
	
### iOS

* In den Einstellungen wählen Sie den Punkt `Persönlicher Hotspot`, anschließend aktiveren Sie `Zugriff für andere erlauben` und vergeben Sie ein `WLAN-Passwort`. Um die erforderliche **5Ghz Frequenzband** für das EZCast Pro Gerät zu unterstützen, bitte deaktivieren Sie `Kompatibilität maximieren`:

![](/assets/img/iphone.enable-hotspot.png)

### Android

* In den Einstellungen wählen Sie den Punkt `Verbindungen` und tippen Sie auf `Mobile Hotspot und Tethering`. Aktivieren Sie die Funktion `Mobile Hotspot` und vergeben Sie ein `Hotspot-Passwort`. Um die erforderliche **5Ghz Frequenzband** für das EZCast Pro Gerät zu unterstützen, bitte wählen Sie `5 GHz bevorzugt`:

![](/assets/img/android.enable-hotspot.png)

## EZCast ProStick II mit WLAN verbinden

Mit Hilfe der Funktion Erweiterte Einstellungen in der `EZCastPro` Software für [Windows und macOS](quickstart.md#InstallSoftware) oder in der App für [Android und iOS](quickstart.md#InstallApp) können Sie Ihr EZCast Pro Gerät mit Ihrem WLAN vebinden.

### Erweiterte Einstellungen öffnen

* Rufen Sie die App bzw. die Software `EZCastPro` auf Ihrem Gerät auf und wählen Sie den Pro Stick II aus der Geräteliste aus.

* Auf Windows/macOS wählen Sie `Erweiterte Einstellungen` unten links:

![](/assets/img/Win-App-Advanced-Settings.png)

* Auf iOS/Android wählen Sie die Schaltfläche `Einstellungen` oben links, anschließend tippen Sie auf `Erweiterte`:

![](/assets/img/iOS_adv-settings.png)

* Geben Sie die IP-Adresse Ihres EZCast Pro Gerätes in einem beliebigen Webbrowser ein, die unter links auf der Startseite angezeigt wird:

![](/assets/img/ProDongleII_connected_to_router.png)

### Sich als Admin anmelden

* Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#hardreset) zurück.

![](/assets/img/EZCastII_Login.png)

### Networkeinstellungen auswählen

* Aus dem Menü oben links wählen Sie `Networkeinstellungen`.

![](/assets/img/ezcastpro.II.select.networkmanagement.png)

* Wählen den Punkt `Mit 5GHz WLAN-Router/AP verbinden` aus.

![](/assets/img/ezcastpro.II.select.connect5ghz.png)

* Verbinden Sie den Pro Stick mit Ihrem WLAN-Router.

![](/assets/img/EZCastPro.II.Wifi.Internet.jpg)

!!! tip "Hinweis"
    
	Bitte beachten: Standardmäßig kann der EZCast Pro Stick II nur mit einem 5GHz WLAN-Router verbunden werden. Sie können jedoch den [Legacy-Modus (2,4 GHz WLAN)](adv.settings.md#legacymode) aktivieren.

* Wenn der EZCast Pro Stick II mit Ihrem Netzwerk bzw. Ihrem Router verbunden ist, wird eine von Ihrem Netzwerk vergebenen IP-Adressen mit der Bezeichnung `Infrustructure IP` auf dem Bildschirm angezeigt, wie unten abgebildet:

![](/assets/img/ProDongleII_connected_to_router.png)

## Problembehandlung

### Internet-Router-Signalstärke

Der EZCast Pro Stick II hat eine Funkreichweite (Sichtlinie) von bis zu 10m. Eine geringe Signalanzeige bezieht sich auf eine schlechte Signalstärke zwischen dem Stick und Ihrem Router bzw. Ihrem Access-Point. Dies kann zu einer abgehackten Wiedergabe von Videos und Inhalten führen, wenn die Inhalte vom Internet abhängig sind oder wenn Ihre Mobilgeräte mit dem Stick über Ihre Infrastruktur verbinden.

Dies kann verschiedene Ursachen und somit verschiedene Lösungen haben:

**1. Problem:** Der Abstand zwischen dem EZCast Pro Stick II und dem Router bzw. Wireless-Access-Point ist zu groß.

Lösung: Versuchen Sie den Abstand zu reduzieren oder installieren Sie einen zusätzlichen Wireless-Access-Point.

**2. Problem:** Es liegen Wände oder andere Gegenstände zwischen dem EZCast Pro Stick II und dem Router bzw. dem Wireless-Access-Point, welche die Signalstärke verschlechtern.

Lösung: Stellen Sie sicher, dass der EZCast Pro Stick II keine Hindernisse zum Router bzw. zum Access-Point hat. Wenn notwendig, installieren Sie einen zusätzlichen Access-Point.

![](/assets/img/ProII.Internet.Signal.png)