# Mit Hotspot verbinden

Sollte Sie Verbindungsprobleme bzw. Abbrüche mit dem EZCast Gerät über Ihre Infrastruktur haben, bitten wir Sie möglicherweise zu Support-Zwecken, dass Sie Ihr EZCast Pro Gerät mit einem Hotspot verbinden und die Leistung vergleichen. Der Hotspot sollte die Bildschirmübertragung von bis zu vier Endgeräten mindestens 30 - 60 Minuten ohne Probleme leisten können. Zu diesem Test benötigen Sie folgende Geräte:

* ein Android Handy bzw. ein iPhone 11 (oder höher), das am Stromnetz angeschlossen ist.

## Hotspot einrichten

!!! tip "Bitte beachten" 
	Prüfen Sie vor Testbeginn, ob das Netzgerät am Android bzw. am iOS-Gerät angeschlossen ist, damit der Hotspot sich während des Tests nicht ausschaltet.
	
### iOS

* In den Einstellungen wählen Sie den Punkt `Persönlicher Hotspot`, anschließend aktiveren Sie `Zugriff für andere erlauben` und vergeben Sie ein `WLAN-Passwort`. Um die erforderliche **5Ghz Frequenzband** für das EZCast Pro Gerät zu unterstützen, bitte deaktivieren Sie `Kompatibilität maximieren`:

![](/assets/img/iphone.enable-hotspot.png)

### Android

* In den Einstellungen wählen Sie den Punkt `Verbindungen` und tippen Sie auf `Mobile Hotspot und Tethering`. Aktivieren Sie die Funktion `Mobile Hotspot` und vergeben Sie ein `Hotspot-Passwort`. Um die erforderliche **5Ghz Frequenzband** für das EZCast Pro Gerät zu unterstützen, bitte wählen Sie `5 GHz bevorzugt`:

![](/assets/img/android.enable-hotspot.png)

## EZCast Pro Gerät mit Hotspot verbinden

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

* Verbinden Sie die Pro Box mit dem Hotspot.

![](/assets/img/EZCastPro.II.Wifi.Internet.jpg)

!!! tip "Hinweis"
    
	Bitte beachten Sie: Standardmäßig kann die EZCast Pro Box II nur mit einem 5GHz WLAN-Router verbunden werden. Sie können jedoch den [Legacy-Modus (2,4 GHz WLAN)](adv.settings.md#legacymode) aktivieren. Für den iOS-Hotspot aktivieren Sie `Kompatibilität maximieren`, für den Android-Hotspot aktivieren Sie unter Bereich `2,4 GHz`.

* Wenn die EZCast Pro Box II mit Ihrem Netzwerk bzw. Ihrem Router verbunden ist, wird eine von Ihrem Netzwerk vergebenen IP-Adressen mit der Bezeichnung `Infrustructure IP` auf dem Bildschirm angezeigt, wie unten abgebildet:

![](/assets/img/ProDongleII_connected_to_router.png)

## Problembehandlung

### WLAN-Signalstärke

Die EZCast Pro Box II hat eine Funkreichweite (Sichtlinie) von bis zu 30m aber der Hotspot eines Handys kann bis zu höchstens 10m funkreichweite leisten. Eine geringe Signalanzeige bezieht sich auf eine schlechte Signalstärke zwischen der Box und Ihrem Hotspot. Dies kann zu einer abgehackten Wiedergabe von Videos und Inhalten führen:

Dies kann verschiedene Ursachen und somit verschiedene Lösungen haben:

**1. Problem:** Der Abstand zwischen der EZCast Pro Box II und dem Hotspot ist zu groß.

Lösung: Versuchen Sie den Abstand zu reduzieren.

**2. Problem:** Es liegen Wände oder andere Gegenstände zwischen der EZCast Pro Box II und dem Hotspot, welche die Signalstärke verschlechtern.

Lösung: Stellen Sie sicher, dass die EZCast Pro Box II keine Hindernisse zum Hotspot.

![](/assets/img/ProII.Internet.Signal.png)