# Firmware neu installieren

Sie können den EZCast Pro Stick II wiederherstellen, indem Sie die Firmware neu installieren. Es gibt mehrere Gründe dafür:

* Der EZCast Pro Stick II lässt sich nicht einschalten. Die Stromversorgung wurde bereits kontrolliert. In diesem Fall kann es an einem unterbrochenen [Aktualisierungs-Vorgang](firmware-upgrade.md) liegen.

* Der EZCast Pro Stick II läuft nicht stabil und ein [Reset](reset.md) hat nicht geholfen.

* Sie haben die Wahl: Entweder die [Neuste Firmware](#neuste-firmware-installieren) oder eine [Vorherige Firmware](#vorherige-firmware-installieren) installieren

> #### info::Hinweis
>
> Bei einer Neuinstallation der Firmware werden **alle** Einstellungen zurückgesetzt.

# Voraussetzung

* Sie benötigen einen Windows Computer, um die Firmware-Software auf dem EZCast Pro Stick II einzuspielen.

* Die Aktualisierung des Firmware-Upgrades muss mit dem mitgelieferten USB Typ C Kabel unter Microsoft Windows vorgenommen werden.

![Das mitgelieferte USB Typ C Kabel](/images/USB-TypeC-Cable.jpg)

# EZCast Pro Repair Tool installieren

* Laden Sie das [EZCast Pro Repair Tool](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/EZCast_Pro_Repair_Tool.zip) herunter.

* Extrahieren Sie die Datei **EZCast_Pro_Repair_Tool.zip**.

![EZCast_Pro_Repair_Tool.zip extrahieren](/images/EZCastPro_Repair_Tool_Extract.jpg) 

* Installieren Sie die Treiber, indem Sie die Batchdatei `EZCast_Pro_Repair_Tool\usb_driver\install.bat` als Administrator ausführen.

![install.bat als Administrator ausführen](/images/EZCastPro_Upgrade_Tool_Run.As.Administrator.jpg)

* Wenn die folgende Sicherheitsmeldung erscheint, wählen Sie **„Installieren“**:

![Wählen Sie Installieren](/images/EZCastPro_Upgrade_Tool_Driver.Install.jpg)


# USB Typ C Kabel anschließen

> #### primary::Hinweis
>
> Anfangs ist das USB Typ C Kabel **nur** mit dem USB-Anschluss des Sticks angeschlossen. Der Stick ist ausgeschaltet. Das andere Ende des Kabels schließen Sie **nachher** mit Ihrem PC an.

* Schließen Sie das mitgelieferte USB Typ C Kabel mit dem USB-Anschluss des Sticks an. Der Stick bleibt ausgeschaltet.

* Um den EZCast Pro Stick II in den Update-Modus zu setzen, drücken und **halten** Sie die Reset-Taste. Schließen Sie anschließend das USB Typ C Kabel mit Ihrem Windows PC an. Nach fünf Sekunden lassen Sie die Reset-Taste los.

![EZCast Pro Stick II in den Update-Modus setzen](/images/ProII-Press-Reset-Button.jpg)

Wenn der Treiber richtig installiert ist und der EZCast Pro Stick II angeschlossen ist, sollte das Gerät **„Realtek generic USB Device“** im Geräte-Manager erscheinen. Wenn nicht, überprüfen Sie die Treiber-Installation, Kabel-Konfiguration, und den Update-Modus, wie im vorherigen Schritt beschrieben.

![EZCastPro Treiber im Geräte-Manager](/images/EZCastPro_Driver.jpg)

# Neuste Firmware installieren

* Im Ordner `EZCast_Pro_Repair_Tool` führen Sie die Datei **EZCastUpdate.exe** aus.

![EZCastUpdate.exe ausführen](/images/EZCastPro_Repair_Tool_EZCastUpdate.exe.jpg)

Das folgende Fenster erscheint. Wenn der EZCast Pro Stick II im Update-Modus ist, wird im Tool „EZCast device connected“ angezeigt.

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

Der EZCast Pro Stick II ist wieder einsatzbereit.

# Vorherige Firmware installieren

Laden Sie eine vorherige Firmware herunter:

Firmware                       | Herunterladen
------------------------- | ------------
1.7545.7 | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.7545.7.gz)
1.7545.1 | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.7545.1.gz)
1.7094.0 | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.7094.0.gz)
1.6557.27 | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.6557.27.gz)
1.6557.21 | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.6557.21.gz)
1.5608.24 | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.5608.24.gz)
1.5608.19 | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.5608.19.gz)
1.4756.0 | [Herunterladen](ftp://ftp.stueber.de/pub/doc/de/ezcastpro/firmwares/D10/D10_1.4756.0.gz)

* Im Ordner `EZCast_Pro_Repair_Tool` führen Sie die Datei **Update_for_localfile.exe** aus.

![localfile.exe ausführen](/images/EZCastPro_Repair_Tool_Update_for_localfile.exe.jpg)

Das folgende Fenster erscheint. Wenn der EZCast Pro Stick II im Update-Modus ist, wird im Tool „EZCast device connected“ angezeigt.

* Mit Hilfe der Schaltfläche `Firmware` wählen Sie die gewünschte Firmwaredatei aus.

![Firmware auswählen](/images/EZCastUpdate.SelectFirmware.jpg)

* Um die Installation der Firmware zu starten, wählen Sie `Upgrade`.

![Wählen Sie Upgrade, um die Installation zu starten](/images/EZCastUpdate.Upgrade.jpg)

Die Firmware wird installiert.

![Die Firmware wird installiert](/images/EZCastUpdate.Firmware.localfile.Updating.jpg)

Wenn die Installation erfolgreich durchgeführt wurde, erscheint die folgende Meldung:

![Die Installation war erfolgreich](/images/EZCastUpdate_localfile.Upgrade.Success.jpg)

Der EZCast Pro Stick II ist wieder einsatzbereit.

# Einstellungen nach der Neuinstallation

Nach der Neuinstallation werden Sie bei der ersten Anmeldung auf der [Erweiterte Einstellungen](adv.settings.md) aufgefordert, das Admin-Kennwort zu ändern. Standardmäßig lautet es `000000`. Wir empfehlen, dass Sie anschließend die folgenden Einstellungen überprüfen:

* [Auflösung](adv.settings.md#Auflösung) z.B.: `AUTO`
* [Mein Bildschirm](adv.settings.md#Mein-Bildschirm) z.B. unsere Startseite in der deutschen Sprache
* [Sprache](adv.settings.md#Sprache) z.B.: `DEUTSCH`
* [WLAN-Modus](adv.settings.md#Wifi-Channel) z.B.: `Land = EUROPE`, `Bandbreite = 20MHz`
* [Android-Audio-Streaming](adv.settings.md#Android-Audio-Streaming) z.B.: `ON`



