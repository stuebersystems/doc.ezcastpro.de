# Einstellungen zurücksetzen

Es gibt mehrere Gründe für einen Zurücksetzen (Reset) der EZCast Pro Box II auf seine Werkseinstellungen:

* Sie haben das Admin-Kennwort für die [Erweiterte Einstellungen](adv.settings.md) vergessen.

* Sie haben Änderungen in Ihrer Netzwerkinfrastruktur, den IP-Einstellungen oder den SSID-Zugangsdaten der Box vorgenommen und Ihre Box ist nicht mehr erreichbar.

* Sie haben Probleme eine ungewollte Änderung auf der Box rückgängig zu machen.

Bei einem Zurücksetzen werden alle Einstellungen zurückgesetzt, außer die [WLAN-SSID](adv.settings.md#Geraetename), das [Hintergrundbild](adv.settings.md#Mein-Bildschirm) der  Startseite und die Firmware-Version.

## Zurücksetzen per App bzw. Software {#softreset}

### Erweiterte Einstellungen öffnen

* Verbinden Sie Ihr Endgerät mit dem EZCast Pro II Gerät, entweder mit der SSID des EZCast Pro II Gerätes oder mit derselben WLAN- bzw. LAN-Infrastruktur, mit welcher das EZCast Pro II Gerät verbunden ist:

![](/assets/img/proII.network.connect.png)

* Geben Sie die IP-Adresse Ihres EZCast Pro Gerätes in einem beliebigen Webbrowser ein, die unten links auf der Startseite angezeigt wird:

![](/assets/img/proII_IP.connect.png)

### Sich als Admin anmelden

* Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#hardreset) zurück.

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

* Mit Hilfe eines kleinen "Stifts" halten Sie den Reset-Schalter ca. 10 Sekunden lang gedrückt. Der Reset-Schalter befindet sich an der Rückseite der Box oben dem USB-Anschluss.

![Reset-Schalter ca. 10 Sekunden lang gedrückt halten](/assets/img/Press-Reset-Button_B10.png)    

* Wenn die folgende Meldung erscheint, lassen Sie den Reset-Schalter los. 

![](/assets/img/Reset_config_complete.png)

*  Bei der Erstanmeldung nach dem Zurücksetzen muss das Land ausgewählt werden:

   ![](/assets/img/wifi.land.selection.png)
   
## Empfohlene Einstellungen {#recommendedsettings}

Die unten empfohlenen Einstellungen setzen voraus, dass Sie ein Zurücksetzen des Empfängers bereits durchgeführt haben:

Firmware-Version: [1.17478.20](whatsnew.md#ezcast-pro-box-ii-firmware-11747820)

**Gerätemanagement**

* [Sprache](adv.settings.md#Sprache): `DEUTSCH`
* [AirPlay-Modus](adv.settings.md#AirPlayMode): `Spiegeln + Video streamen`
* [AirView](adv.settings.md#AirView): `EIN`
* [Castcode](adv.settings.md#Castcode): `Zufällig`
* [Miracast Pin-Code](adv.settings.md#Miracast): `EIN`
* [Miracast Geteilter Bildschirm](adv.settings.md#Miracast): `Geteilter Bildschirm unterstützt`
* [Zeitgesteuerter Neustart](adv.settings.md#timedrestart): `2 Stunden`

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