# Einstellungen zurücksetzen

Es gibt mehrere Gründe für einen Zurücksetzen (Reset) des EZCast Pro Stick II auf seine Werkseinstellungen:

* Sie haben das Admin-Kennwort für die [Erweiterte Einstellungen](adv.settings.md) vergessen.

* Sie haben Änderungen in Ihrer Netzwerkinfrastruktur, den IP-Einstellungen oder den SSID-Zugangsdaten des Sticks vorgenommen und Ihr Stick ist nicht mehr erreichbar.

* Sie haben Probleme eine ungewollte Änderung auf dem Stick rückgängig zu machen.

Bei einem Zurücksetzen werden alle Einstellungen zurückgesetzt, außer die [WLAN-SSID](adv.settings.md#Geraetename), das [Hintergrundbild](adv.settings.md#Mein-Bildschirm) der  Startseite und die Firmware-Version.

## Zurücksetzen per App bzw. Software {#softreset}

Mit Hilfe der Funktion Erweiterte Einstellungen in der `EZCastPro` Software für [Windows und macOS](quickstart.md#InstallSoftware) oder in der App für [Android und iOS](quickstart.md#InstallApp) können Sie  die Standardeinstellungen zurücksetzen.

### Erweiterte Einstellungen öffnen

* Rufen Sie die App bzw. die Software `EZCastPro` auf Ihrem Gerät auf und wählen Sie den Pro Stick II aus der Geräteliste aus.

* Auf Windows/macOS wählen Sie `Erweiterte Einstellungen` unten links:

![](/assets/img/Win-App-Advanced-Settings.png)

* Auf iOS/Android wählen Sie die Schaltfläche `Einstellungen` oben links, anschließend tippen Sie auf `Erweiterte`:

![](/assets/img/iOS_adv-settings.png)

### Sich als Admin anmelden

* Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#zurücksetzen-per-reset-schalter) zurück.

![](/assets/img/EZCastII_Login.png)

### Auf Standardeinstellungen zurücksetzen

* Aus dem Menü oben links wählen Sie `Admineinstellungen`.

![](/assets/img/ezcastpro.II.select.admineinstellungen.png)

* Wählen den Punkt `Auf Standardeinstellungen zurücksetzen` aus.

![](/assets/img/ezcastpro.II.Standardeinstellungen.zuruecksetzen.png)

* Zum Bestätigen wählen Sie `Ja`.

![](/assets/img/Reset.png)


## Zurücksetzen per Reset-Schalter {#hardreset}

Wenn Ihnen die Zugangsdaten für die [Erweiterte Einstellungen](adv.settings.md) nicht bekannt sind, haben Sie die Möglichkeit mit dem Reset-Schalter die Standardeinstellungen zurückzusetzen:

* Wenn die Stromversorgung angeschlossen ist, halten Sie den Reset-Schalter ca. 10 Sekunden lang gedrückt. Der Reset-Schalter befindet sich an der Seite des Sticks neben dem USB-Anschluss.

![Reset-Schalter ca. 10 Sekunden lang gedrückt halten](/assets/img/ProII-Press-Reset-Button.jpg)

* Wenn die folgende Meldung erscheint, lassen Sie den Reset-Schalter los.

![](/assets/img/Reset_config_complete.png)

*  Bei der Erstanmeldung nach dem Zurücksetzen muss das Land ausgewählt werden:

   ![](/assets/img/wifi.land.selection.png)
   
## Einstellungen nach dem Zurücksetzen {#recommendedsettings}

Nach dem Zurücksetzen werden Sie bei der ersten Anmeldung auf der Funktion [Erweiterte Einstellungen](adv.settings.md) aufgefordert, das Admin-Kennwort zu ändern. Standardmäßig lautet es `000000`. Wir empfehlen, dass Sie anschließend die folgenden Einstellungen überprüfen:

Firmware-Version: 1.12170.15

**Gerätemanagement**

* [Sprache](adv.settings.md#Sprache): `DEUTSCH`
* [Android Audioübertragung](adv.settings.md#Android-Audio-Streaming): `EIN`
* [AirView](adv.settings.md#AirView): `EIN`
* [Castcode](adv.settings.md#Castcode): `Zufällig`
* [Zeitgesteuerter Neustart](adv.settings.md#timedrestart): `EIN`

**Netzwerkmanagement**

* [WLAN-Modus](adv.settings.md#Wifi-Channel): `Land = EUROPE`, `Kanal = Auto`, `Bandbreite = 20MHz`

**Admineinstellungen**

* [Host-Berechtigungen](adv.settings.md#Host-permissions):
    * `Konferenzsteuerung = Ein`
    * `Netzwerkmanagement = Aus`
    * `Gerätemanagement = Aus`
    * `Neustart = Ein`
* [Mein Bildschirm](adv.settings.md#Mein-Bildschirm): unsere [Startseite](https://download.stueber.de/doc/de/ezcastpro/EZCastProV2_StartseiteDE.png) in der deutschen Sprache
* [Zentrales Managementsystem](adv.settings.md#AirView): `EIN`


