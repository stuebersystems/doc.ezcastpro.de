# Firmware neu installieren

Sie können den EZCast Pro Stick II wiederherstellen, indem Sie die Firmware neu installieren. Es gibt mehrere Gründe dafür:

* Der EZCast Pro Stick II lässt sich nicht einschalten. Die Stromversorgung wurde bereits kontrolliert. In diesem Fall kann es an einem unterbrochenen [Aktualisierungs-Vorgang](firmware-upgrade.md) liegen.

* Der EZCast Pro Stick II läuft nicht stabil und ein [Reset](reset.md) hat nicht geholfen.

Sie haben die Wahl: Installieren Sie entweder einfach die neuste Firmware oder eine andere Firmware.


## Firmware über USB-Kabel installieren

!!! warning "Achtung"
    
	Bei einer Neuinstallation der Firmware werden **alle** Einstellungen zurückgesetzt.
	
### Voraussetzung

* Sie benötigen einen Windows Computer, um die Firmware-Software auf dem EZCast Pro Stick II einzuspielen.

* Die Aktualisierung des Firmware-Upgrades muss mit dem mitgelieferten USB Typ C Kabel unter Microsoft Windows vorgenommen werden.

![Das mitgelieferte USB Typ C Kabel](/assets/img/USB-TypeC-Cable.jpg)

### EZCast Pro Repair Tool installieren

* Laden Sie das [EZCast Pro Stick II (D10) Repair Tool](https://download.stueber.de/doc/de/ezcastpro/repair_tools/EZCastPro.D10.Repair.Tool.zip) herunter.

* Extrahieren Sie die Datei **EZCastPro.D10.Repair.Tool.zip**.

![EZCastPro.D10.Repair.Tool.zip extrahieren](/assets/img/D10.Repair_Tool_Extract.png) 

* Installieren Sie die Treiber, indem Sie die Batchdatei `EZCastPro.D10.Repair.Tool\usb_driver\install.bat` als Administrator ausführen.

![install.bat als Administrator ausführen](/assets/img/D10.install.bat.png)

* Wenn die folgende Sicherheitsmeldung erscheint, wählen Sie **„Installieren“**:

![Wählen Sie Installieren](/assets/img/EZCastPro_Upgrade_Tool_Driver.Install.png)

### USB Typ C Kabel anschließen

!!! hint "Hinweis"

    Anfangs ist das USB Typ C Kabel **nur** mit dem USB-Anschluss des Sticks angeschlossen. Der Stick ist ausgeschaltet. Das andere Ende des Kabels schließen Sie **nachher** mit Ihrem PC an.

* Schließen Sie das mitgelieferte USB Typ C Kabel mit dem USB-Anschluss des Sticks an. Der Stick bleibt ausgeschaltet.

* Um den EZCast Pro Stick II in den Update-Modus zu setzen, drücken und **halten** Sie die Reset-Taste. Schließen Sie anschließend das USB Typ C Kabel mit Ihrem Windows PC an. Nach fünf Sekunden lassen Sie die Reset-Taste los.

![EZCast Pro Stick II in den Update-Modus setzen](/assets/img/ProII-Press-Reset-Button.jpg)

Wenn der Treiber richtig installiert ist und der EZCast Pro Stick II angeschlossen ist, sollte das Gerät **„Realtek generic USB Device“** im Geräte-Manager erscheinen. Wenn nicht, überprüfen Sie die Treiber-Installation, Kabel-Konfiguration, und den Update-Modus, wie im vorherigen Schritt beschrieben.

![EZCastPro Treiber im Geräte-Manager](/assets/img/EZCastPro_Driver.jpg)

### Neuste Firmware installieren

* Im Ordner `EZCastPro.D10.Repair.Tool` führen Sie die Datei **EZCastUpdate.exe** aus.

![EZCastUpdate.exe ausführen](/assets/img/D10.Repair_Tool_Update.exe.png)

Das folgende Fenster erscheint. Wenn der EZCast Pro Stick II im Update-Modus ist, wird im Tool „EZCast device connected“ angezeigt.

* Wählen Sie `Download`, um die neuste Firmware herunterzuladen.

![Die Schaltfläche Download wählen](/assets/img/EZCastUpdate.DeviceConnected.jpg)

Das Downloaden der Firmware wird durchgeführt.

!!! warning "Achtung"

    Sie dürfen den Strom während der Aktualisierung nicht unterbrechen.

![EZCastPro Firmware wird heruntergefahren](/assets/img/EZCastUpdate.Firmware.Downloading.jpg)

* Um die Installation der Firmware zu starten, wählen Sie `Upgrade`.

![Wählen Sie Upgrade, um die Installation zu starten](/assets/img/EZCastUpdate.Upgrade.jpg)

Die Firmware wird installiert.

![Die Firmware wird installiert](/assets/img/EZCastUpdate.Firmware.Updating.jpg)

Wenn die Installation erfolgreich durchgeführt wurde, erscheint die folgende Meldung:

![Die Installation war erfolgreich](/assets/img/EZCastUpdate_Upgrade.Success.jpg)

Der EZCast Pro Stick II ist wieder einsatzbereit.

### Andere Firmware installieren

Um eine vorherige bzw. eine Betafirmware zu installieren, laden Sie eine der folgenden Dateien herunter:

Firmware                       | Herunterladen | Bemerkung
------------------------- | ------------ | ------------
1.13739.0 (Beta) | [Herunterladen](https://download.stueber.de/doc/de/ezcastpro/firmwares/D10/D10_1.13739.0.gz) | neues Modul AirPlay mit Onscreen-Code
1.12170.25  (Beta) | [Herunterladen](https://download.stueber.de/doc/de/ezcastpro/firmwares/D10/D10_1.12170.25.gz) | CMS-Stabilität verbessert
1.12170.19 | [Herunterladen](https://download.stueber.de/doc/de/ezcastpro/firmwares/D10/D10_1.12170.19.gz)
1.12170.16 | [Herunterladen](https://download.stueber.de/doc/de/ezcastpro/firmwares/D10/D10_1.12170.16.gz)
1.9871.34 | [Herunterladen](https://download.stueber.de/doc/de/ezcastpro/firmwares/D10/D10_1.9871.34.gz)


* Im Ordner `EZCastPro.D10.Repair.Tool` führen Sie die Datei **Update_for_localfile.exe** aus.

![Update_for_localfile.exe ausführen](/assets/img/D10.localfile.exe.png)

Das folgende Fenster erscheint. Wenn der EZCast Pro Stick II im Update-Modus ist, wird im Tool „EZCast device connected“ angezeigt.

* Mit Hilfe der Schaltfläche `Firmware` wählen Sie die gewünschte Firmwaredatei aus.

![Firmware auswählen](/assets/img/EZCastUpdate.SelectFirmware.jpg)

* Um die Installation der Firmware zu starten, wählen Sie `Upgrade`.

![Wählen Sie Upgrade, um die Installation zu starten](/assets/img/EZCastUpdate.Upgrade.jpg)

Die Firmware wird installiert.

![Die Firmware wird installiert](/assets/img/EZCastUpdate.Firmware.localfile.Updating.jpg)

Wenn die Installation erfolgreich durchgeführt wurde, erscheint die folgende Meldung:

![Die Installation war erfolgreich](/assets/img/EZCastUpdate_localfile.Upgrade.Success.jpg)

Der EZCast Pro Stick II ist wieder einsatzbereit.

!!! warning "Achtung"

    Bei einer Neuinstallation der Firmware werden die fabrikseitigen Einstellungen des Geräts wiederhergestellt. Bitte prüfen Sie nach der Neuinstallation unsere [empfohlene Einstellungen](reset.md#recommendedsettings).


## Firmware mit dem CMS installieren

Mit dem CMS ([Central Management System](cms.md)) kann man nicht nur die aktuelle Firmware vom Internet auf mehreren EZCast Pro II Geräten bzw. QuattroPod installieren, sondern auch eine vorherige Version bzw. eine Beta-Firmware.

* Laden Sie eine Firmware von der obigen Tabelle [andere Firmware](#andere-firmware-installieren) herunter.

* Wählen Sie die gewünschten Geräte aus, anschließend klicken Sie auf die Schaltfläche `Remote` -> und die Funktion `Device Firmware upgrade`.

![Die Firmware wird installiert](/assets/img/CMS-firmware.upgrade1.png)

* Unter der Registerkarte `FILE`, wählen die Schaltfläche `File` und wählen Sie die Firmwaredatei aus, die Sie im ersten Schritt heruntergeladen haben.

![Die Firmware wird installiert](/assets/img/CMS-firmware.upgrade2.png)

Die neue Firmware wird heruntergeladen und automatisch installiert. 

!!! warning "Achtung"
    
	Unterbrechen Sie während des Updates nicht die Stromversorgung.

![](/assets/img/ProIIStick_Firmware_installing.png)

## Einstellungen nach der Neuinstallation {#recommendedsettings}

Bei einer Neuinstallation der Firmware werden alle Einstellungen zurückgesetzt. Unsere empfohlene Einstellungen finden Sie [hier](reset.md#recommendedsettings).

