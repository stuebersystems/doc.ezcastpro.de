# Was ist AirPlay?

AirPlay ist die Übertragungstechnologie von Apple zur kabellosen Übertragung von Apple-Geräten auf AirPlay-fähige Empfängergeräte wie Lautsprecher, AV-Empfänger, Stereosysteme und Fernseher.

Der EZCast Pro Stick II ermöglicht es bis zu vier macOS und iOS-Geräten, über das AirPlay-Protokoll auf einem aufgeteilten Bildschirm gemeinsam zu übertragen, ohne die App zu benötigen.

!!! info "iOS-Gerät-Bildschirmübertragung mit EZCast Pro"

    [![EZCast Pro LAN Box Einführungsvideo][1]{: align=left }][2]
	
	Ein kurzes Video, das die Bildschirmübertragung per iPhone vorstellt.
	
	[Zum YouTube-Video][2]

  [1]: /assets/img/thumbnail.video.airplay.png
  [2]: https://youtu.be/UMHHFNFskMQ
  
## AirPlay freischalten

Standardmäßig ist AirPlay auf EZCast Pro II-Geräten aktiviert. Sollten Sie die Funktion jedoch erneut aktivieren wollen, finden Sie die entsprechende Option `AirPlay` unter [Erweiterte Einstellungen](adv.settings.md#AirPlayMode):

![](/assets/img/ezcastpro.II.AirPlay.Settings.png)

Eine umfassende Anleitung zur Verwendung von **AirPlay PIN** finden Sie [hier](securitycodes.md/#airplay-pin):

## AirPlay auf iOS

Um Ihren iOS-Bildschirm zu übertragen, verbinden Sie Ihr Gerät mit demselben WLAN-Netzwerk wie EZCast Pro. Die SSID und das Kennwort von EZCast Pro werden oben auf der Startseite angezeigt:

![EZCast Pro Startseite](/assets/img/ProIIDongle_landingpage.png)

![EZCast Pro Startseite](/assets/img/iOS_WiFi-Connect.png)

Auf Ihrem iOS-Gerät streichen Sie vom unteren Bildschirmrand nach oben, um das Kontrollzentrum aufzurufen.

![Kontrollzentrum öffnen](/assets/img/iOS-controlcenter.png)

Im Kontrollzentrum tippen Sie auf `Bildschirmsynchronisierung`, anschließend wählen Sie den EZCast Pro Stick II aus.

!!! tip "Hinweis"

     Wenn der EZCast Pro Empfänger unter AirPlay nicht zu sehen ist, stellen Sie sicher, dass Ihr iOS-Gerät mit dem Empfänger verbunden ist. AWDL (Apple Wireless Direct Link) ist Apples proprietäres Mesh-Netzwerkprotokoll, mit dem Apple-Geräte im Nahbereich Ad-hoc-Peer-to-Peer-Mesh-Netzwerke nutzen können. Dieses Protokoll wird für EZCast Pro Geräte nicht verwendet.

![Der EZCast Pro Empfänger](/assets/img/iOS_AirPlay_select.png)

Um die Übertragung von AirPlay vom iOS-Gerät zu beenden, tippen Sie nochmal auf `Bildschirmsynchronisierung` im Kontrollzentrum, anschließend wählen Sie `Synchronisierung stoppen` aus.

![Synchronisierung stoppen](/assets/img/iOS_AirPlay_stop.png)

## AirPlay auf macOS

Um Ihren macOS-Bildschirm zu übertragen, verbinden Sie Ihr Gerät mit demselben WLAN-Netzwerk wie EZCast Pro. Die SSID von EZCast Pro wird oben auf der Startseite angezeigt:

![EZCast Pro Startseite](/assets/img/ProIIDongle_landingpage.png)

In the Mac menu bar, klicken Sie auf das AirPlay-Symbol ![](/assets/img/airplay_icon.png) oben im Bildschirm.

Wählen Sie das gewünschte EZCast Pro Gerät in der Liste aus. Wenn es nicht angezeigt wird, vergewissern Sie sich, dass Ihr Mac mit demselben Netzwerk wie das EZCast Pro-Gerät verbunden ist.

![AirPlay: Select EZCast Pro Stick II](/assets/img/macOS-AirPlay.png)

## Video-Streamen aktivieren

Sie möchten ein Video aus dem Internet mit Ihrem iPad (4:3 Bildformat) auf einen 16:9 Full-HD Bildschirm ruckelfrei und ohne schwarze Ränder abspielen? Für das beste Videostreaming-Erlebnis empfehlen wir das Aktivieren der Funktion **Spiegeln + Video streamen**:

* Diese Funktion ist unter [Gerätemanagement -> AirPlay-Modus](adv.settings.md#AirPlayMode) zu finden:

![Video-Streamen im Vollbild aktivieren](/assets/img/ezcastpro.II.EZAir_Mode.enable.videostreaming.png)

**Voraussetzungen**

Die Funktion `Spiegeln + Video streamen` benötigt die Firmware-Version `1.13781.68` oder höher. Wenn die Startseite erscheint, prüfen Sie, ob die erfolderliche Mindestversion angezeigt wird, wie unten abgebildet. Wenn nötig, [aktualisieren](firmware-upgrade.md) Sie bitte Ihre Firmware.

![](/assets/img/ProIIDongle_Firmware-Version.png)

!!! info "Hinweis"

    Das Aktivieren der Funktion **Spiegeln + Video-Streamen** wird nach einem Neustart des EZCast Pro Gerätes wirksam.
	
Um ein Video im Vollbild auf den großen Bildschirm zu übertragen, nutzen Sie einfach die [Bildschirmsynchronisierung](#airplay-auf-ios) Funktion von AirPlay. Wenn Sie im Videoplayer „Vollbild“ wählen, wechselt das EZCast Pro Gerät in einen Vollbildmodus. Das Endgerät zeigt "Mit AirPlay verbunden" und das Video wird im Vollbild auf den großen Bildschirm gestreamt:

![](/assets/img/ipad.video.stream.png)

Ohne die Aktivierung der Funktion `Spiegeln + Video streamen` wird der Bildschirm des iPads einfach gespiegelt. Schwarze Ränder sind zu sehen und die Übertragung kann ruckelig werden:

![](/assets/img/ipad.video.mirror.png)

!!! info "Hinweis"

    Die YouTube App unter iOS unterstützt keinen geteilten Bildschirm und kann keine Inhalte übertragen, während ein anderes Gerät gespiegelt wird. Möchten Sie gleichzeitiges Senden (Splitscreen mit bis zu 4 Geräten) unterstützen, muss das Video in einem Webbrowser z.B. Safari oder Google Chrome abgespielt werden. 