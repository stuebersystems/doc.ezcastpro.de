# Firmware neu installieren

Sie können die EZCast Pro Box II wiederherstellen, indem Sie die Firmware neu installieren. Es gibt mehrere Gründe dafür:

* Die EZCast Pro Box II lässt sich nicht einschalten. Die Stromversorgung wurde bereits kontrolliert. In diesem Fall kann es an einem unterbrochenen [Aktualisierungs-Vorgang](firmware-upgrade.md) liegen.

* Die EZCast Pro Box II läuft nicht stabil und ein [Reset](reset.md) hat nicht geholfen.

* Sie haben die Wahl: Installieren Sie entweder einfach die neuste Firmware oder eine andere Firmware.

## Firmware über USB-Kabel installieren

!!! warning "Achtung"

    Bei einer Neuinstallation der Firmware werden **alle** Einstellungen zurückgesetzt.

### Voraussetzung

* Sie benötigen einen Windows Computer, um die Firmware-Software auf der EZCast Pro Box II einzuspielen.

* Die EZCast Pro Box II muss mit Ihrem Windows-PC per [USB Kabel (A/A)](https://www.amazon.de/deleyCON-Super-Speed-Kabel-Stecker/dp/B00WHZ746E/ref=sr_1_3?ie=UTF8&qid=1531928442&sr=8-3&keywords=usb+kabel+male+to+male) angeschlossen werden.

![USB Kabel-Kabel AA ](/assets/img/USB-Kabel-AA.jpg)

### EZCast Pro Repair Tool installieren

* Laden Sie das [EZCast Pro Box II (B10) Repair Tool](https://download.stueber.de/doc/de/ezcastpro/repair_tools/EZCastPro.B10.Repair.Tool.zip) herunter.

* Extrahieren Sie die Datei **EZCastPro.B10.Repair.Tool.zip**.

![EZCastPro.B10.Repair.Tool.zip extrahieren](/assets/img/EZCastPro_Repair_Tool_Extract.jpg) 

* Installieren Sie die Treiber, indem Sie die Batchdatei `EZCast_Pro_Repair_Tool\usb_driver\install.bat` als Administrator ausführen.

![install.bat als Administrator ausführen](/assets/img/EZCastPro_Upgrade_Tool_Run.As.Administrator.jpg)

* Wenn die folgende Sicherheitsmeldung erscheint, wählen Sie **„Installieren“**:

![Wählen Sie Installieren](/assets/img/EZCastPro_Upgrade_Tool_Driver.Install.png)


### USB Typ A Kabel anschließen

!!! warning "Achtung"

    Anfangs ist das USB Typ A Kabel **nur** mit dem USB-Anschluss der Box angeschlossen. Die Box ist ausgeschaltet. Das andere Ende des Kabels schließen Sie **nachher** mit Ihrem PC an.

* Um die EZCast Pro Box II in den Update-Modus zu setzen, schalten Sie das Gerät per die Power-Taste aus. Mit Hilfe eines kleinen "Stifts" halten Sie den Reset-Schalter gedrückt. Schalten Sie das Gerät per die Power-Taste ein, anschließend können Sie den Reset-Schalter loslassen.

![EZCast Pro Box II in den Update-Modus setzen](/assets/img/Press-Reset-Button_B10.png)

* Schließen Sie nun das [USB Kabel (A/A)](https://www.amazon.de/deleyCON-Super-Speed-Kabel-Stecker/dp/B00WHZ746E/ref=sr_1_3?ie=UTF8&qid=1531928442&sr=8-3&keywords=usb+kabel+male+to+male) an den USB-Port der Box und an einen USB-Port Ihres Rechners unter Microsoft Windows an.

![Empfänger mit Ihrem PC per USB-Kabel (A/A) anschließen](/assets/img/IMG_4504_M.png)

Wenn der Treiber richtig installiert ist und die EZCast Pro Box II angeschlossen ist, sollte das Gerät **„Realtek generic USB Device“** im Geräte-Manager erscheinen. Wenn nicht, überprüfen Sie die Treiber-Installation, Kabel-Konfiguration, und den Update-Modus, wie im vorherigen Schritt beschrieben.

![EZCastPro Treiber im Geräte-Manager](/assets/img/EZCastPro_Driver.jpg)

### Neuste Firmware installieren

* Im Ordner `EZCast_Pro_Repair_Tool` führen Sie die Datei **EZCastUpdate.exe** aus.

![EZCastUpdate.exe ausführen](/assets/img/EZCastPro_Repair_Tool_EZCastUpdate.exe.jpg)

Das folgende Fenster erscheint. Wenn die EZCast Pro Box II im Update-Modus ist, wird im Tool „EZCast device connected“ angezeigt.

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

Die EZCast Pro Box II ist wieder einsatzbereit.

### Andere Firmware installieren

Um eine vorherige bzw. eine Betafirmware zu installieren, laden Sie eine der folgenden Dateien herunter:

Firmware                       | Herunterladen | Bemerkung
------------------------- | ------------ | ------------
1.13781.15 | [Herunterladen](https://download.stueber.de/doc/de/ezcastpro/firmwares/B10/B10_1.13781.15.gz)
1.12170.19 | [Herunterladen](https://download.stueber.de/doc/de/ezcastpro/firmwares/B10/B10_1.12170.19.gz)
1.12170.16 | [Herunterladen](https://download.stueber.de/doc/de/ezcastpro/firmwares/B10/B10_1.12170.16.gz)
1.9871.37 | [Herunterladen](https://download.stueber.de/doc/de/ezcastpro/firmwares/B10/B10_1.9871.37.gz)

* Im Ordner `EZCast_Pro_Repair_Tool` führen Sie die Datei **Update_for_localfile.exe** aus.

![Update_for_localfile.exe ausführen](/assets/img/EZCastPro_Repair_Tool_Update_for_localfile.exe.jpg)

Das folgende Fenster erscheint. Wenn die EZCast Pro Box II im Update-Modus ist, wird im Tool „EZCast device connected“ angezeigt.

* Mit Hilfe der Schaltfläche `Firmware` wählen Sie die gewünschte Firmwaredatei aus.

![Firmware auswählen](/assets/img/EZCastUpdate.SelectFirmware.jpg)

* Um die Installation der Firmware zu starten, wählen Sie `Upgrade`.

![Wählen Sie Upgrade, um die Installation zu starten](/assets/img/EZCastUpdate.Upgrade.jpg)

Die Firmware wird installiert.

![Die Firmware wird installiert](/assets/img/EZCastUpdate.Firmware.localfile.Updating.jpg)

Wenn die Installation erfolgreich durchgeführt wurde, erscheint die folgende Meldung:

![Die Installation war erfolgreich](/assets/img/EZCastUpdate_localfile.Upgrade.Success.jpg)

Die EZCast Pro Box II ist wieder einsatzbereit.

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

