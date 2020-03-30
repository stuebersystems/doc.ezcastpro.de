# Firmware neu installieren

Sie können die EZCast Pro Box II wiederherstellen, indem Sie die Firmware neu installieren. Es gibt mehrere Gründe dafür:

* Die EZCast Pro Box II lässt sich nicht einschalten. Die Stromversorgung wurde bereits kontrolliert. In diesem Fall kann es an einem unterbrochenen [Aktualisierungs-Vorgang](firmware-upgrade.md) liegen.

* Die EZCast Pro Box II läuft nicht stabil und ein [Reset](reset.md) hat nicht geholfen.

* Sie haben die Wahl: Installieren Sie entweder einfach die [neuste Firmware](#neuste-firmware-installieren) oder eine [andere Firmware](#andere-firmware-installieren)

> #### info::Hinweis
>
> Bei einer Neuinstallation der Firmware werden **alle** Einstellungen zurückgesetzt.

# Voraussetzung

* Sie benötigen einen Windows Computer, um die Firmware-Software auf der EZCast Pro Box II einzuspielen.

* Die EZCast Pro Box II muss mit Ihrem Windows-PC per [USB Kabel (A/A)](https://www.amazon.de/deleyCON-Super-Speed-Kabel-Stecker/dp/B00WHZ746E/ref=sr_1_3?ie=UTF8&qid=1531928442&sr=8-3&keywords=usb+kabel+male+to+male) angeschlossen werden.

![USB Kabel-Kabel AA ](/images/USB-Kabel-AA.jpg)

# EZCast Pro Repair Tool installieren

* Laden Sie das [EZCast Pro Repair Tool](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/EZCast_Pro_Repair_Tool.zip) herunter.

* Extrahieren Sie die Datei **EZCast_Pro_Repair_Tool.zip**.

![EZCast_Pro_Repair_Tool.zip extrahieren](/images/EZCastPro_Repair_Tool_Extract.jpg) 

* Installieren Sie die Treiber, indem Sie die Batchdatei `EZCast_Pro_Repair_Tool\usb_driver\install.bat` als Administrator ausführen.

![install.bat als Administrator ausführen](/images/EZCastPro_Upgrade_Tool_Run.As.Administrator.jpg)

* Wenn die folgende Sicherheitsmeldung erscheint, wählen Sie **„Installieren“**:

![Wählen Sie Installieren](/images/EZCastPro_Upgrade_Tool_Driver.Install.jpg)


# USB Typ A Kabel anschließen

> #### primary::Hinweis
>
> Anfangs ist das USB Typ A Kabel **nur** mit dem USB-Anschluss der Box angeschlossen. Die Box ist ausgeschaltet. Das andere Ende des Kabels schließen Sie **nachher** mit Ihrem PC an.


* Um die EZCast Pro Box II in den Update-Modus zu setzen, schalten Sie das Gerät per die Power-Taste aus. Mit Hilfe eines kleinen "Stifts" halten Sie den Reset-Schalter gedrückt. Schalten Sie das Gerät per die Power-Taste ein, anschließend können Sie den Reset-Schalter loslassen.

![EZCast Pro Box II in den Update-Modus setzen](/images/Press-Reset-Button_B10.jpg)
* Schließen Sie nun das [USB Kabel (A/A)](https://www.amazon.de/deleyCON-Super-Speed-Kabel-Stecker/dp/B00WHZ746E/ref=sr_1_3?ie=UTF8&qid=1531928442&sr=8-3&keywords=usb+kabel+male+to+male) an den USB-Port der Box und an einen USB-Port Ihres Rechners unter Microsoft Windows an.

Wenn der Treiber richtig installiert ist und die EZCast Pro Box II angeschlossen ist, sollte das Gerät **„Realtek generic USB Device“** im Geräte-Manager erscheinen. Wenn nicht, überprüfen Sie die Treiber-Installation, Kabel-Konfiguration, und den Update-Modus, wie im vorherigen Schritt beschrieben.

![EZCastPro Treiber im Geräte-Manager](/images/EZCastPro_Driver.jpg)

# Neuste Firmware installieren

* Im Ordner `EZCast_Pro_Repair_Tool` führen Sie die Datei **EZCastUpdate.exe** aus.

![EZCastUpdate.exe ausführen](/images/EZCastPro_Repair_Tool_EZCastUpdate.exe.jpg)

Das folgende Fenster erscheint. Wenn die EZCast Pro Box II im Update-Modus ist, wird im Tool „EZCast device connected“ angezeigt.

* Wählen Sie `Download`, um die neuste Firmware herunterzuladen.

![Die Schaltfläche Download wählen](/images/EZCastUpdate.DeviceConnected.jpg)

Das Downloaden der Firmware wird durchgeführt.

> #### primary::Hinweis
>
> Sie dürfen den Strom während der Aktualisierung nicht unterbrechen.

![EZCastPro Firmware wird heruntergefahren](/images/EZCastUpdate.Firmware.Downloading.jpg)

* Um die Installation der Firmware zu starten, wählen Sie `Upgrade`.

![Wählen Sie Upgrade, um die Installation zu starten](/images/EZCastUpdate.Upgrade.jpg)

Die Firmware wird installiert.

![Die Firmware wird installiert](/images/EZCastUpdate.Firmware.Updating.jpg)

Wenn die Installation erfolgreich durchgeführt wurde, erscheint die folgende Meldung:

![Die Installation war erfolgreich](/images/EZCastUpdate_Upgrade.Success.jpg)

Die EZCast Pro Box II ist wieder einsatzbereit.

# Andere Firmware installieren

Um eine vorherige bzw. eine Betafirmware zu installieren, laden Sie eine der folgenden Dateien herunter:

Firmware                       | Herunterladen
------------------------- | ------------
1.7545.10 (Beta) | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.7545.10.gz)
1.7545.7 | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.7545.7.gz)
1.7545.1 | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.7545.1.gz)
1.7094.0 | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.7094.0.gz)
1.6557.27 | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.6557.27.gz)
1.6557.21 | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.6557.21.gz)
1.5608.24 | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.5608.24.gz)
1.5608.19 | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.5608.19.gz)
1.4756.0 | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.4756.0.gz)

* Im Ordner `EZCast_Pro_Repair_Tool` führen Sie die Datei **Update_for_localfile.exe** aus.

![Update_for_localfile.exe ausführen](/images/EZCastPro_Repair_Tool_Update_for_localfile.exe.jpg)

Das folgende Fenster erscheint. Wenn die EZCast Pro Box II im Update-Modus ist, wird im Tool „EZCast device connected“ angezeigt.

* Mit Hilfe der Schaltfläche `Firmware` wählen Sie die gewünschte Firmwaredatei aus.

![Firmware auswählen](/images/EZCastUpdate.SelectFirmware.jpg)

* Um die Installation der Firmware zu starten, wählen Sie `Upgrade`.

![Wählen Sie Upgrade, um die Installation zu starten](/images/EZCastUpdate.Upgrade.jpg)

Die Firmware wird installiert.

![Die Firmware wird installiert](/images/EZCastUpdate.Firmware.localfile.Updating.jpg)

Wenn die Installation erfolgreich durchgeführt wurde, erscheint die folgende Meldung:

![Die Installation war erfolgreich](/images/EZCastUpdate_localfile.Upgrade.Success.jpg)

Die EZCast Pro Box II ist wieder einsatzbereit.

> #### info::HINWEIS
>
> Bitte beachten: Bei einer Neuinstallation der Firmware werden die fabrikseitigen Einstellungen des Geräts wiederhergestellt. Bitte prüfen Sie nach der Neuinstallation unsere [empfohlene Einstellungen](#Recommendedsettings).


# Einstellungen nach der Neuinstallation {#Recommendedsettings}

Nach der Neuinstallation werden Sie bei der ersten Anmeldung auf der [Erweiterte Einstellungen](adv.settings.md) aufgefordert, das Admin-Kennwort zu ändern. Standardmäßig lautet es `000000`. Wir empfehlen, dass Sie anschließend die folgenden Einstellungen überprüfen:

* [Mein Bildschirm](adv.settings.md#Mein-Bildschirm): [Unsere Startseite](https://download.stueber.de/doc/de/ezcastpro/EZCastProV2_StartseiteDE.png) in der deutschen Sprache
* [Sprache](adv.settings.md#Sprache): `DEUTSCH`
* [WLAN-Modus](adv.settings.md#Wifi-Channel): `Land = EUROPE`, `Bandbreite = 20MHz`
* [Android-Audio-Streaming](adv.settings.md#Android-Audio-Streaming): `EIN`
* [Gastbehörde](adv.settings.md#Host-Authority):

Dem Host Zugang nur auf die Konferenzsteuerung und die Reboot-Steuerung zulassen:

`Admineinstellungen` -> `Gastbehörde`
	
![](/images/Host_authority.jpg)

