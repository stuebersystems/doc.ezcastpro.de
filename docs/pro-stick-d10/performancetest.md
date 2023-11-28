# Latenz- und Leistungstest durchführen

Zu Support-Zwecken bitten wir Sie möglicherweise, dass Sie einen Latenztest oder einen Leistungstest Ihres EZCast Pro Gerätes durchführen. Bei korrekter Bedienung sollte die Latenzzeit einer Videoübertragung in Full-HD (1920 x 1080, 60Hz) bei ca 0,2 Sekunden und in UHD (3840 x 2060, 30Hz) bei ca 0,7 Sekunden liegen. Außerdem sollte das Abspielen eines Videos für mindestens 6 Stunden möglich sein.

Ein solcher Test wurde im untenstehenden Video durchgeführt:

[![Leistungstest](/assets/img/thumbnail.video.performancetest1.png)](https://assets.stueber.de/videos/latencetest.mp4)

!!! tip "Hinweis"

     Vor Testbeginn stellen Sie unbedingt sicher, dass Sie unsere [Einrichtungsempfehlungen](select.display.type.md) für den EZCast Pro Stick II sowie die [Netzwerkvoraussetzungen](connect.wifi.md#voraussetzungen) sorgfältig durchgelesen haben. Außerdem empfehlen wir ein [Firmwareupdate](firmware-upgrade.md) und [Zurücksetzen](reset.md) des Gerätes, um sicherzustellen, dass Sie mit der optimalen Konfiguration des Gerätes arbeiten.
	 
## Latenztest

In dieser Anleitung beschreiben wir, wie Sie einen Latenztest mit einem Windows-PC durchführen. Selbstverständlich können Sie den Test mit anderen Endgeräten durchführen.

### Videodatei herunterladen

* Zuerst laden Sie das untenstehende Latenztest-Video auf Ihrem Windows-PC herunter:

[![Leistungstest-Video](/assets/img/thumbnail.video.performancetest2.png "test")](https://assets.stueber.de/videos/performancetest.mp4)

* Spielen Sie das Video in Ihrem Media-Player ab:

![](/assets/img/video.open.in.mediaplayer.png)

### Bildschirmübertragung durchführen

Bevor Sie mit dem Latenztest beginnen, empfehlen wir, die folgenden beiden Vorsichtsmaßnahmen zu treffen:

* [Trennen Sie](connect.wifi.md#vom-wlan-trennen) den EZCast Pro Stick II von der WLAN-Netzwerkinfrastruktur, um jeglichen externen Einfluss zu vermeiden. Dies bedeutet, dass Sie nur die Verbindung von Ihrem Endgerät zum EZCast Pro-Gerät testen werden. Sie können später das WLAN wieder verbinden und den Test erneut durchführen.

* Führen Sie den Test auf einem EZCast Pro Stick II mit der [neuesten Firmware](firmware-upgrade.md) durch, das [zurückgesetzt](reset.md) und mit unseren [empfohlenen Einstellungen](reset.md#recommendedsettings) konfiguriert wurde.
	 
Wir empfehlen zwei Möglichkeiten die Bildschirmübertragung als Latenztest unter Windows durchzuführen:

#### Miracast unter Windows: 

Drücken Sie die Tastenkombination `[Windows]` + `[K]`, um das Dialogfenster `VERBINDEN` aufzurufen. Wählen Sie den EZCast Pro Gerät aus:

![EZCast Pro Stick auswählen](/assets/img/ProIIStick-Windows_Miracast_Select_Device.jpg)

Eine umfassende Anleitung zur Verwendung von Miracast unter Windows finden Sie [hier](miracast.md#miracast-auf-windows):

#### EZCast Pro Software

* Verbinden Sie Ihr Notebook mit der SSID, die oben auf dem Bildschirm angezeigt wird. Das Kennwort wird standardmäßig ebenfalls angezeigt.

	![](/assets/img/proII.notebook.direct.connect.png)

* Rufen Sie die Software **EZCastPro** auf Ihrem Gerät auf:

    ![Starten Sie die Software EZCastPro](/assets/img/EZCastPro_Start_Software.png)

* Wählen Sie die EZCast Pro Box II aus, wie unten abgebildet:

    ![Die Geräteliste](/assets/img/mac-windows_device-list.png)

* Zum Spiegeln Ihres Windows/macOS Geräts wählen Sie `Spiegeln`:

    ![Ihr Windows/Mac-Gerät spiegeln](/assets/img/mac-windows_mirror.png)

Eine umfassende Anleitung zur Verwendung von der EZCast Pro Software unter Windows finden Sie [hier](quickstart.md#b-erweiterte-funktion-ezcast-pro-software):

![](/assets/img/QSG-TypeC.Windows.png)

!!! tip "Hinweis"

     Lassen Sie die Bildschirmübertragung so lange wie möglich laufen. Sollte die Übertragung abgebrochen werden, lassen Sie uns eine [Log-Datei](logfile.md) zukommen.

### Latenzzeit kontrollieren

* Während das Video abgespielt wird, machen Sie ein Foto mit Ihrem Handy und ziehen Sie den auf Ihrem Endgerät angezeigten Wert oben links von dem auf dem Large Screen bzw. von dem Beamer angezeigten Wert ab. Dies zeigt die Latenzzeit der Übertragung:

![Latency Test](/assets/img/latency.test.png)

## Langer Leistungstest

In dieser Anleitung beschreiben wir, wie Sie einen langen Leistungstest mit einem Windows-Rechner durchführen. Sie können selbstverständlich einen Test mit anderen Endgeräten durchführen. Stellen Sie einfach sicher, dass die das Endgerät vor Testbeginn während des Tests nicht in den Energiesparmodus wechselt bzw. sich nicht ausschaltet.

### Auto Mouse Mover herunterladen {#automousemover}

* Damit der Windows-PC während des Test nicht in den Energiesparmodus wechselt, laden Sie die Software [![Auto Mouse Mover](/assets/img/automousemover.icon.png)](https://www.murgee.com/auto-mouse-mover/) [Auto Mouse Mover](https://www.murgee.com/auto-mouse-mover/), die Variante **Stand Alone Application**, herunter und extrahieren Sie die .zip-Datei auf Ihrem Windows-PC:

![](/assets/img/automousemover.extract.png)

* Führen Sie die Datei **AutoMouseMover.exe** aus:

![](/assets/img/AutoMouseMover.exe.png)

* Auf der Lizenzvereinbarung wählen Sie `Accept`:

![](/assets/img/automousemover.agreement.png)

* Sie können die vorgegebenen Einstellungen übernehmen und einfach auf `Save & Hide to System Tray` klicken, um die Software in die Systemleiste zu minimieren:

![](/assets/img/automousemove.settings.png)

### Videodatei wiederholend abspielen

* Laden Sie folgendes [MP4-Video](https://assets.stueber.de/videos/performancetest.mp4) auf Ihrem Windows-PC herunter:

[![Leistungstest-Video](/assets/img/thumbnail.video.performancetest2.png)](https://assets.stueber.de/videos/performancetest.mp4)

* Öffen Sie das Video im **Windows Media Player**: 

![](/assets/img/video.open.in.mediaplayer.png)

* Aktivieren Sie auf die Wiederholungstaste:

![](/assets/img/mediaplayer.repeat.png)

* Das Video wird wiederholt abgespielt und auf das große Display übertragen:

![](/assets/img/video.playing.png)

### Bildschirmübertragung durchführen

Bevor Sie mit dem Latenztest beginnen, empfehlen wir, die folgenden beiden Vorsichtsmaßnahmen zu treffen:

* [Trennen Sie](connect.wifi.md#vom-wlan-trennen) den EZCast Pro Stick II von der WLAN-Netzwerkinfrastruktur, um jeglichen externen Einfluss zu vermeiden. Dies bedeutet, dass Sie nur die Verbindung von Ihrem Endgerät zum EZCast Pro-Gerät testen werden. Sie können später das WLAN wieder verbinden und den Test erneut durchführen.

* Führen Sie den Test auf einem EZCast Pro Stick II mit der [neuesten Firmware](firmware-upgrade.md) durch, das [zurückgesetzt](reset.md) und mit unseren [empfohlenen Einstellungen](reset.md#recommendedsettings) konfiguriert wurde.
	 
Wir empfehlen zwei Möglichkeiten die Bildschirmübertragung als Latenztest unter Windows durchzuführen:

#### Miracast unter Windows: 

Drücken Sie die Tastenkombination `[Windows]` + `[K]`, um das Dialogfenster `VERBINDEN` aufzurufen. Wählen Sie den EZCast Pro Gerät aus:

![EZCast Pro Stick auswählen](/assets/img/ProIIStick-Windows_Miracast_Select_Device.jpg)

Eine umfassende Anleitung zur Verwendung von Miracast unter Windows finden Sie [hier](miracast.md#miracast-auf-windows):

#### EZCast Pro Software

* Verbinden Sie Ihr Notebook mit der SSID, die oben auf dem Bildschirm angezeigt wird. Das Kennwort wird standardmäßig ebenfalls angezeigt.

	![](/assets/img/proII.notebook.direct.connect.png)

* Rufen Sie die Software **EZCastPro** auf Ihrem Gerät auf:

    ![Starten Sie die Software EZCastPro](/assets/img/EZCastPro_Start_Software.png)

* Wählen Sie die EZCast Pro Box II aus, wie unten abgebildet:

    ![Die Geräteliste](/assets/img/mac-windows_device-list.png)

* Zum Spiegeln Ihres Windows/macOS Geräts wählen Sie `Spiegeln`:

    ![Ihr Windows/Mac-Gerät spiegeln](/assets/img/mac-windows_mirror.png)

Eine umfassende Anleitung zur Verwendung von der EZCast Pro Software unter Windows finden Sie [hier](quickstart.md#b-erweiterte-funktion-ezcast-pro-software):

![](/assets/img/QSG-TypeC.Windows.png)

!!! tip "Hinweis"

     Lassen Sie die Bildschirmübertragung so lange wie möglich laufen. Sollte die Übertragung abgebrochen wird, lassen Sie uns eine [Log-Datei](logfile.md) zukommen lassen.