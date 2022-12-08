# Firmware aktualisieren

## Warum aktualisiert man die Firmware? 

Um von den neuesten Funktionen der EZCast Pro Box II zu profitieren, können Sie das neueste Firmware-Update schnell und bequem über das Internet installieren. Bei der Installation einer neuen Firmware werden die bisherigen Einstellungen mitgenommen. Dabei benötigt das EZCast Pro Gerät einen Internetzugang. Dies wird mit dem WLAN-Symbol oben rechts und eine vergebene IP-Adresse Ihres Routers mit der Bezeichnung `Infrustructure IP` unten links auf der Startseite anzeigt, wie unten abgebildet:

![](/assets/img/ProII_fw.upgrade.available.png)

Wenn Ihre EZCast Pro Box II nicht mit dem Internet verbunden ist, prüfen Sie das [WLAN/LAN](connect.wifi.lan.md).

## Firmware per Web-Oberfläche aktualisieren

### Erweiterte Einstellungen öffnen

* Verbinden Sie Ihr Endgerät mit dem EZCast Pro II Gerät, entweder mit der SSID des EZCast Pro II Gerätes oder mit derselben WLAN- bzw. LAN-Infrastruktur, mit welcher das EZCast Pro II Gerät verbunden ist:

![](/assets/img/proII.network.connect.png)

* Geben Sie die IP-Adresse Ihres EZCast Pro Gerätes in einem beliebigen Webbrowser ein, die unten links auf der Startseite angezeigt wird:

![](/assets/img/proII_IP.connect.png)

### Sich als Admin anmelden

* Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#hardreset) zurück.

![](/assets/img/EZCastII_Login.png)

### Upgrade ausführen

*   Aus dem Menü wählen Sie die `Admineinstellungen` aus:

    ![](/assets/img/ezcastpro.II.select.admineinstellungen.png)

*   Wenn eine neue Firmware-Version zur Verfügung steht, wird es mit `Neue Version!` neben dem Menüpunkt `Aktualisierung` angezeigt. Um fortzusetzen wählen Sie diese Schaltfläche aus:

    ![](/assets/img/ProIIStick_Startseite_Firmware-Menuoption.png)

*   Die neue Firmware-Version wird im Feld Server-Version angezeigt. Zum bestätigen wählen Sie `Aktualisierung`.

    ![](/assets/img/ProIIStick_Start.Upgrade.jpg)

Die neue Firmware wird heruntergeladen und automatisch installiert. 

!!! warning "Achtung"
    
	Unterbrechen Sie während des Updates nicht die Stromversorgung.

![](/assets/img/ProIIStick_Firmware_installing.png)

Nach dem Neustart wird die aktuelle Version der Firmware unten rechts auf der Startseite angezeigt:

![](/assets/img/ProIIDongle_Firmware-Version.png)

## Firmware per Internet mit dem CMS installieren

Mit dem CMS ([Central Management System](cms.md)) kann man die neueste Firmware vom Internet auf mehreren EZCast Pro II bzw. QuattroPod Geräten installieren.

* Wenn eine neue Firmware für den Empfänger bzw. für den Sender zur Verfügung steht, taucht die Meldung ![](/assets/img/CMS-firmware.available.png) neben dem Gerät auf:

![Die Firmware wird installiert](/assets/img/CMS-firmware.OTA.select.devices.png)

* Wählen Sie die gewünschten Geräte aus, anschließend klicken Sie auf die Schaltfläche `Remote` -> und wählen Sie die Funktion `Device firmware upgrade`.

![Die Firmware wird installiert](/assets/img/CMS-firmware.install.latest.firmware.png)

* Unter der Registerkarte `OTA`, klicken Sie einfach auf die Schaltfläche `Apply`, um die Aktualisierung durchzuführen:

![Die Firmware wird installiert](/assets/img/CMS-firmware.upgrade.OTA.png)

Die neue Firmware wird heruntergeladen und automatisch installiert. 

* Während der Aktualisierung des Empfängers erscheint folgende Meldung:

![Firmware-Version aktualisieren](/assets/img/ProIIStick_Firmware_installing.png)

!!! warning "Achtung"
    
	Unterbrechen Sie während des Updates nicht die Stromversorgung.

## Firmware ohne Internet mit dem CMS installieren

Mit dem CMS ([Central Management System](cms.md)) ermöglicht es Ihnen auch, die neueste Firmware auf Geräten zu installieren, die nicht mit dem Internet verbunden sind. Bitte nutzen Sie die untenstehenden Links, um die Firmware für Ihre Geräte vorab herunterzuladen:

Geräte               | Herunterladen      |
------------------------- | ------------------------- | 
Pro Stick II | [Herunterladen](../pro-stick-d10/firmware-reinstall.md#D10_install_other_fw)
Pro Box II | [Herunterladen](firmware-reinstall.md#B10_install_other_fw)

* Wählen Sie die gewünschten Geräte aus, klicken Sie dann auf die Schaltfläche `Remote` und wählen Sie die Option `Device firmware upgrade`.

![](/assets/img/CMS-firmware.install.latest.firmware.png)

* Unter Registerkarte `FILE`, wählen Sie die Firmware-Datei aus, die Sie zuvor heruntergeladen haben:

![](/assets/img/CMS-firmware.upgrade2.png)

* Klicken Sie auf die Schaltfläche `Apply`, um die Aktualisierung durchzuführen:

![](/assets/img/CMS-firmware.upgrade.FILE.apply.png)

* Während der Aktualisierung des Empfängers erscheint folgende Meldung:

![](/assets/img/ProIIStick_Firmware_installing.png)

!!! warning "Achtung"
    
	Unterbrechen Sie während des Updates nicht die Stromversorgung.
	
## Einstellungen nach der Firmware-Aktualiserung {#recommendedsettings}

Nach einer Firmware-Aktualiserung überprüfen Sie alle Einstellungen und neue Funktionen, die zur Verfügung. Unsere empfohlene Einstellungen [finden Sie hier](reset.md#recommendedsettings).

!!! tip "Hinweis"
    
	Wenn Sie die Funktion Erweiterte Einstellungen in einem Webbrowser statt in der EZCast Pro App/Software ansehen, leeren Sie bitte nach der Aktualisierung der Firmware den Browser-Cache, um alle neu verfügbaren Optionen zu sehen.