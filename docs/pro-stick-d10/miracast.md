# Über Miracast verbinden

Mit Miracast haben Sie die Möglichkeit, Windows-Geräte (Windows 8.1 oder höher) oder Android-Geräte (Android 4.4 oder höher) mit dem EZCast Pro Gerät ohne App/Software zu präsentieren. Das EZCast Pro II Gerät ermöglicht es bis zu vier Geräte inkl. Geräte über das Miracast-Protokoll auf einem aufgeteilten Bildschirm gemeinsam zu übertragen, ohne die App zu benötigen.

!!! hint "Miracast mit Android und EZCast Pro II"

    [![Miracast mit Android und EZCast Pro II][1]{: align=left }][2]
	
	Anleitung: Bildschirmübertragung von Android über Miracast mit EZCast Pro II
	
	[Video ansehen][2]

  [1]: /assets/img/miracast-android.video.png
  [2]: https://assets.stueber.de/videos/d10.android.de.mp4

## Miracast auf Windows

Um Miracast mit dem EZCast Pro II Gerät zu verbinden, stellen Sie sicher, dass der Empfänger eingeschalten ist und die Startseite auf dem Bildschirm angezeigt ist.

![EZCast Pro Stick II Startseite](/assets/img/ProIIDongle_landingpage.png)

Drücken Sie die Tastenkombination `[Windows]` + `[K]`, um das Dialogfenster `VERBINDEN` aufzurufen. Wählen Sie den EZCast Pro Gerät aus:

![EZCast Pro Stick auswählen](/assets/img/ProIIStick-Windows_Miracast_Select_Device.jpg)

Eine Verbindung über Miracast wird hergestellt:

![Miracast-Verbindung wird hergestellt](/assets/img/ProIIStick-Windows_Miracast_Connecting.jpg)

Der Aufbau der Miracast-Verbindung dauert 5 bis 10 Sekunden. Während dieser Zeit sind drei Punkte oben rechts auf der Startseite zu sehen:

![Miracast-Verbindung wird hergestellt](/assets/img/miracast_connecting.png)

Sie sind nun mit Ihrem Bildschirm per Miracast verbunden. Eine zusätzliche Anzeige taucht in der Systemsteuerung auf. Anzeige-Einstellungen z.B. Auslösung und Skalierung können Sie anpassen, wie gewünscht.

![Miracast-Anzeige in der Systemsteuerung](/assets/img/Miracast_Display.jpg)

Um die Miracast-Anzeige zu trennen, rufen Sie das Dialogfenster erneut `VERBINDEN` auf, indem Sie die Tastenkombination `[Windows]` + `[K]` drücken und klicken Sie auf `Trennen`:

![Drahtlose Anzeige trennen](/assets/img/ProIIStick-Windows_Miracast_Disconnect.jpg)

## Miracast auf Android

Um Miracast mit dem EZCast Pro Stick II zu verbinden, stellen Sie sicher, dass der Empfänger eingeschalten ist und die Startseite auf dem Bildschirm angezeigt ist.

![EZCast Pro Stick II Startseite](/assets/img/ProIIDongle_landingpage.png)

Auf Ihrem Android-Gerät streichen Sie vom unteren Bildschirmrand nach oben, um das **Kontrollzentrum** aufzurufen und wählen Sie die Anwendung zur Bildschirmübertragung. Bei den meisten Geräten heißt es `Drahtlosprojektion`, `Smart View` oder auch `Screen Mirroring`. Wählen Sie anschließend Ihr EZCast Pro Gerät aus. Um die Bildschirmübertragung zum beenden, wählen Sie `Trennen` in selben Bereich.

![Screen Mirroring](/assets/img/miracast.android.png)

## Die zwei Miracast-Modi {#miracast-modes}

Mit EZCast Pro II stehen zwei verschiedende Modi **Vollbildmodus** und **Geteilter Bildschirm** zur Verfügung. Diese zwei Modi bieten unterschiedliche Funktionalität. Wir liefern Ihr EZCast Pro Gerät mit dem Modus **Geteilter Bildschirm**. Sie haben allerdings die Wahl, auf den anderen Modus mithilfe der Funktion [Erweiterte Einstellungen](adv.settings.md) unter `Gerätemanagement` -> `Miracast` umzuschalten.

![](/assets/img/Miracast.AGO.mode.png)

### Geteilter Bildschirm (AGO-Modus) {#ago-mode}

Mit der Firmware [1.12170.16](whatsnew.md#ezcast-pro-stick-ii-firmware-11217016) wurde der Modus **Geteilter Bildschirm**, auch bekannt als AGO-Modus (Autonomous Group Owner in englischer Sprache), eingeführt, um eine Bildschirmübertragung nativ, also ohne die zusätzliche EZCast Pro App/Software, von bis zu 4 Geräten einschließlich Miracast-Geräten auf einem geteilten Bildschirm zu ermöglichen. 

Ist der Miracast-Modus **Geteilter Bildschirm** aktiviert, wird der Gerätename bzw. die auf der Startseite angezeigte SSID mit dem Präfix `DIRECT-` ergänzt. Dies gilt für die SSID des EZCast Pro Gerätes, die in Ihren WLAN-Einstellungen zu finden ist, sowie den angezeigten Gerätenamen unter den Streamingprotokollen AirView und Chromecast: 

![](/assets/img/ago.SSID.png)

Der angezeigte Gerätename bei der Suche nach verfügbaren Geräten unter Miracast wird allerdings **nicht** mit dem Präfix ergänzt. Dies ist erforderlich, um das Miracast-Protokoll sowie alle anderen Streamingprotokolle gemeinsam zu unterstützen:

![](/assets/img/ProIIStick-Windows_Miracast_Select_Device.jpg)

In diesem Modus gelten die folgenden Eigenschaften:

* Der geteilte Bildschirm unterstützt alle Streamingprotokolle mit bis zu 4 Geräten einschließlich Miracast-Geräten. 
* Die SSID bzw. der Gerätename kann geändert werden, aber enthält immer vorne den Präfix "DIRECT-", beispielsweise `DIRECT-Raum_001`. 
* Das Kennwort kann nicht in diesem Modus geändert werden. Um das Kennwort zu ändern, schalten Sie bitte zuerst das EZCast Pro Gerät auf [Vollbildmodus](#ngo-mode) um, dann nehmen Sie die Änderung des Kennworts vor, anschließend schalten Sie wieder auf [Geteilter Bildschirm](#ngo-mode) um.
* Das Kennwort kann nicht ausgeblendet werden. Um das Kennwort auszublenden, schalten Sie bitte zuerst das EZCast Pro Gerät auf [Vollbildmodus](#ngo-mode) um, dann stellen Sie das Ausblenden des Kennworts ein, anschließend schalten Sie wieder auf [Geteilter Bildschirm](#ngo-mode) um.
* [Infracast](#p2p_vs_infracast) wird nicht unterstützt.
* Während der Bildschirmübertragung eines Miracast-Gerätes bleiben alle Netzwerkschnittstellen erreichbar und alle Funktionen stehen weiterhin zur Verfügung.

Sollten Sie die Option `Admineinstellungen` -> `Verbindung` -> [Nur über Router](adv.settings.md#networkinterfaces) aktiviert haben, wird das Stick-WLAN trotzdem ausgestrahlt. Dies ist erforderlich, um diesen Miracast-Modus zu unterstützen. Das Kennwort wird allerdings ausgeblendet. Daher erfolgt die Bildschirmübertragung nur über P2P mit Miracast, oder über Router mit AirPlay, Google Cast, EZCast Pro App.

![](/assets/img/AGO_via_Router.png)

### Vollbildmodus (NGO-Modus) {#ngo-mode}

Im Modus **Vollbildmodus**, auch bekannt als NGO-Modus (Negotiated Group Owner in englischer Sprache), gelten die folgenden Eigenschaften:

* Der geteilte Bildschirm wird unter dem Miracast-Protokoll nicht unterstützt. Mit Miracast kann nur ein Gerät im Vollbild übertragen werden. Um eine Bildschirmübertragung von bis zu 4 Geräten einschließlich Windows/Android-Geräten auf einem geteilten Bildschirm zu ermöglichen, müssen diese Geräte ein anderes Protokoll nutzen z.B. Google Google Cast oder die EZCast Pro Software/App. Wenn eine Bildschirmübertragung nativ, also ohne zusätzliche EZCast Pro App/Software, von bis zu 4 Geräten einschließlich Miracast-Geräten auf einem geteilten Bildschirm gewünscht ist, muss das EZCast-Gerät auf den Modus [Geteilter Bildschirm](#ago-mode) umgeschaltet werden. 
* Die SSID bzw. der Gerätename kann vollständig geändert werden, beispielsweise `Raum_001`. 
* Das Kennwort kann geändert werden.
* Das Kennwort kann ausgeblendet werden.
* [Infracast](#p2p_vs_infracast) wird unterstützt.
* Während der Bildschirmübertragung eines Miracast-Gerätes werden alle Netzwerkschnittstellen belegt, kein weiteres Endgerät kann gespiegelt werden und die folgenden Funktionen **stehen nicht zur Verfügung**:
    * Die Moderator-Funktion bzw. die [Host-Kontrolle](ezcastproapp.md#hostcontrol).
	* [CMS (Central Management System)](/cms/intro/).
    * [AirView](ezcastproapp.md#airview).
    * [Konferenzsteuerung](ezcastproapp.md#conferencecontrol).
    * Die Web-Oberfläche der [Einstellungen](adv.settings.md).
	
## P2P vs. Infracast {#p2p_vs_infracast}

Es gibt zwei Arten von Miracast-Verbindungen, **P2P** und **Infracast**, die von Windows 10-Geräten aus möglich sind:

### P2P (Peer-to-Peer)

Der WiFi-Direct-Standard (Peer-to-Peer), der ein direktes Verbinden zweier WLAN-fähiger Geräte ohne zwischengeschalteten Access Point (AP) gestattet. Es gelten die folgenden Eigenschaften:

* Wird ab Windows 8.1 oder höher unterstützt.
* Keine WLAN-Infrastruktur erfolderlich.
* Wird unter beiden Modi **Vollbildmodus** und **Geteilter Bildschirm** unterstützt.
* Maximalabstand von 10 Meter zwischen dem EZCast Pro Stick II und dem Endbenutzer muss berücksichtigt werden.

Es ist möglich während der Bildschirmübertragung, mithilfe des Windows Task-Managers festzustellen, ob ein PC über P2P verbunden ist: 

* Öffnen Sie den Task-Manager und wählen Sie die Registerkarte `Leistung`. Wenn P2P in Verwendung ist, wird die SSID bzw. der Gerätename des EZCast Pro Gerätes unter einem zusätzlichen Netzwerkadapter **Wi-Fi Direct** angezeigt und wird mit dem Präfix `DIRECT-` ergänzt:

![](/assets/img/D10.BF8E0C84.NGO-mode.Space-in-SSID.png)

### Infracast (Miracast über Infrastruktur)

Die Daten der Bildschirmübertragung werden über ein lokales Netzwerk anstatt über eine P2P-Verbindung gesendet. Weitere Informationen sind im [Microsoft-Artikel](https://docs.microsoft.com/de-de/surface-hub/miracast-over-infrastructure) zu finden.

Eine Miracast-Verbindung mit dem EZCast Pro Gerät über Infrastruktur wird hergestellt, sofern folgende Voraussetzungen erfüllt sind:

* Wird ab Windows 10 Version 1703 und höher unterstützt.
* Wird nur im [Vollbildmodus (NGO-Modus)](#ngo-mode) unterstützt.
* Die SSID bzw. der Gerätename des EZCast Pro Gerätes darf kein Leerzeichen enthalten:
    * RICHTIG: `Raum_001`
    * FALSCH: `Raum 001`
* Es werden auch Windows-Geräte über LAN-Kabel unterstützt.
* Es wird kein PIN bzw. kein Sicherheitscode unterstützt.
* Das Windows-Gerät und das EZCast Pro Gerät müssen sich im gleichen Netzwerk befinden.
* Maximalabstand von 10 Meter zwischen dem EZCast Pro Stick II und dem AccessPoint muss berücksichtigt werden.
	
Für den Endbenutzer ist der Prozess zur Initiierung einer Miracast-P2P oder Infracast-Verbindung gleich. Man drückt die Tastenkombination `[Windows]` + `[K]`, um das Dialogfenster `VERBINDEN` aufzurufen, dann wählt man den Empfänger aus der Liste der verfügbaren Geräte aus. 

Während der Bildschirmübertragung ist es mithilfe des Windows Task-Managers möglich festzustellen, ob ein PC über Infracast verbunden ist: 

* Öffnen Sie den Task-Manager und wählen Sie die Registerkarte `Leistung`.

Wenn Infracast in Verwendung ist, wird nur der bisherige Netzwerkadapter mit Angaben zu Ihrer Infrastruktur angezeigt:

![](/assets/img/D10_BF8E0C84.NGO-mode.No-Space-in-SSID.png)

### Problembehandlung

#### Es konnte keine Verbindung hergestellt werden

Wenn Miracast-Einstellungen bzw. der Gerätename des EZCast Pro Gerätes geändert werden, kann es dazu führen, dass Miracast sich nicht verbinden lässt. Um das Problem zu lösen, löschen Sie bitte den Eintrag der Miracast-Verbindung in den Windows-Einstellungen, anschließend verbinden Sie Ihr Endgerät erneut:

![](/assets/img/Miracast.failed-to-connect.png)

##### Windows 10 Miracast-Eintrag löschen

* Im Startmenü öffenen Sie die `Einstellungen`: 

![](/assets/img/Miracast.win11.delete.record1.png)

![](/assets/img/Miracast.win11.delete.record2.png)

![](/assets/img/Miracast.win11.delete.record3.png)

##### Windows 11 Miracast-Eintrag löschen

* Im Startmenü öffenen Sie die `Einstellungen`: 

![](/assets/img/Miracast.win10.delete.record1.png)

![](/assets/img/Miracast.win10.delete.record2.png)