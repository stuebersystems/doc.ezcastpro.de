# Firmware neu installieren

Sie können die EZCast Pro Box II wiederherstellen, indem Sie die Firmware neu installieren. Es gibt mehrere Gründe dafür:

* Die EZCast Pro Box II lässt sich nicht einschalten. Die Stromversorgung wurde bereits kontrolliert. In diesem Fall kann es an einem unterbrochenen [Aktualisierungs-Vorgang](firmware-upgrade.md) liegen.

* Die EZCast Pro Box II läuft nicht stabil und ein [Reset](reset.md) hat nicht geholfen.

* Sie haben die Wahl: Installieren Sie entweder einfach die neuste Firmware oder eine andere Firmware.

> #### info::Hinweis
>
> Bei einer Neuinstallation der Firmware werden **alle** Einstellungen zurückgesetzt.

# Voraussetzung

* Sie benötigen einen Windows Computer, um die Firmware-Software auf der EZCast Pro Box II einzuspielen.

* Die EZCast Pro Box II muss mit Ihrem Windows-PC per [USB Kabel (A/A)](https://www.amazon.de/deleyCON-Super-Speed-Kabel-Stecker/dp/B00WHZ746E/ref=sr_1_3?ie=UTF8&qid=1531928442&sr=8-3&keywords=usb+kabel+male+to+male) angeschlossen werden.

![USB Kabel-Kabel AA ](/images/USB-Kabel-AA.jpg)

# EZCast Pro Repair Tool installieren

* Laden Sie das [EZCast Pro Repair Tool](http://download.stueber.de/doc/de/ezcastpro/EZCast_Pro_Repair_Tool.zip) herunter.

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

![Empfänger mit Ihrem PC per USB-Kabel (A/A) anschließen](/images/B10_rear.jpg)

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
1.8617.21 | [Herunterladen](http://download.stueber.de/doc/de/ezcastpro/firmwares/B10/B10_1.8617.21.gz)
1.8617.18 | [Herunterladen](http://download.stueber.de/doc/de/ezcastpro/firmwares/B10/B10_1.8617.18.gz)
1.7545.8 | [Herunterladen](http://download.stueber.de/doc/de/ezcastpro/firmwares/B10/B10_1.7545.8.gz)
1.7545.1 | [Herunterladen](http://download.stueber.de/doc/de/ezcastpro/firmwares/B10/B10_1.7545.1.gz)

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
> Bitte beachten: Bei einer Neuinstallation der Firmware werden die fabrikseitigen Einstellungen des Geräts wiederhergestellt. Bitte prüfen Sie nach der Neuinstallation unsere [empfohlene Einstellungen](reset.md#recommendedsettings).


# Einstellungen nach der Neuinstallation {#recommendedsettings}

Bei einer Neuinstallation der Firmware werden alle Einstellungen zurückgesetzt. Unsere empfohlene Einstellungen finden Sie [hier](reset.md#recommendedsettings).

