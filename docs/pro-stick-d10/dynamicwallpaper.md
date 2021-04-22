# Dynamisches Hintergrundbild

## Was ist ein Dynamisches Hintergrundbild?

Das dynamische Hintergrundbild, ist eine Funktion, die nach einer einstellbaren Zeit der Inaktivität automatisch gestartet wird und eine Sammlung von Bildern bzw. Videos auf dem Bildschirm anzeigt. Es dient folgenden Zwecken:

* Bildschirmschoner-Funktion

* Werbezwecke in Geschäften

* Public Display / Digital Signage

## Erstellen einer JSON-Datei

Gehen Sie wie folgt vor:

* Öffnen Sie den Windows-Editor (oder einen anderen Texteditor) und erzeugen Sie eine neue leere Datei.

* Kopieren Sie die JSON-Textblöcke in den Texteditor, die unter zu finden sind und ändern Sie den Inhalt nach Ihren Wünschen ab. Für zusätzliche Einträge kopieren Sie die Abschnitte, die in geschweiften Klammern `{}` eingeschlossen sind, so oft wie nötig.


### Inhalte aus dem Internet

Unsere Beispieldatei `wallpaper_file.json` steht Ihnen [hier](https://download.stueber.de/doc/de/content/wallpaper_file.json) zum Download zur Verfügung. 

```` xml
{
   "slideshow": [
		{
         "image_url": "https://download.stueber.de/doc/de/content/pic1.jpg",
         "attribution": "Test Picture 1",
         "duration": 10,
		},
		{
         "image_url": "https://download.stueber.de/doc/de/content/pic2.jpg",
         "attribution": "Test Picture 2",
         "duration": 10,
		},
		{
         "url": "https://download.stueber.de/doc/de/content/video1.mp4",
         "title": "EZCast Pro Stick II",
		},  	  	       
	],
	"next": ""
}
````

!!! info "Hinweis"

    Es werden nur die Dateiformate `.MP4` und `.JPG` unterstützt.

* Speichern Sie die Datei als `wallpaper_file.json` ab und laden Sie die Datei auf einen Webserver hoch, auf den das EZCast Pro Gerät zugreifen kann.


### JSON-Syntax

* `image_url` Der Pfad zur Bilddatei.

* `attribution` Das Titel der.

* `duration` Die Anzeigedauer der Bilddatei.

* `url` Der Pfad zur Bilddatei.


## Wie legt man das Dynamische Hintergrundbild fest?

Mit Hilfe der Funktion Erweiterte Einstellungen in der `EZCastPro` Software für [Windows und macOS](quickstart.md#InstallSoftware) oder in der App für [Android und iOS](quickstart.md#InstallApp) können Sie die Funktion Dynamisches Hintergrundbild einstellen.

### Erweiterte Einstellungen öffnen

* Rufen Sie die Software `EZCastPro`auf Ihrem Gerät auf und wählen Sie die Pro Box II aus der Geräteliste aus.

* Auf Windows/macOS wählen Sie `Erweiterte Einstellungen`.

![](/assets/img/Win-App-Advanced-Settings.png)

* Auf iOS/Android wählen Sie die Schaltfläche `Einstellungen` oben links, anschließend tippen Sie auf `Erweiterte`:

![](/assets/img/iOS_adv-settings.png)

### Sich als Admin anmelden

* Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#zurücksetzen-per-reset-schalter) zurück.

![](/assets/img/EZCastII_Login.png)

* Während der ersten Anmeldung, müssen Sie das Admin-Kennwort ändern. Danach müssen Sie sich noch einmal anmelden.

![](/assets/img/new_password.png)

### Dynamisches Hintergrundbild einstellen

* Aus dem Menü wählen Sie `Admineinstellungen` aus:

![](/assets/img/ezcastpro.II.select.adminsettings.png)

Nach Anmeldung  wählen Sie die Option dynamisches Hintergrundbild und schalten Sie die ein.

![Host Control](/assets/img/dyn.hintergrund.ein.png)

* `Dynamisches Hintergrund` - Aktivieren Sie diesen Punkt, um die Funktion freizuschalten.

* `Silent-Modus` - Wenn Sie keinen Ton hören möchten, aktivieren Sie diesen Punkt.

![](/assets/img/Dynamic.Wallpaper.activate.png)

Wenn Inhalte aus dem Intenet abgespielt werden sollen, wählen Sie die Registerkarte `URL` und geben Sie den Pfad zur JSON-Datei an. 

![Host Control](/assets/img/Dynamic.Wallpaper.URL.png)

Wenn Inhalte auf einem USB-Stick abgespielt werden sollen, wählen Sie die Registerkarte `USB Disk` und geben Sie den Pfad zur JSON-Datei an. 

![Host Control](/assets/img/Dynamic.Wallpaper.USB.png)

Geben Sie eine Dauer von Inaktivität in Minuten an, bevor die Funktion Dynamisches Hintergrundbild ausgeführt werden soll:

![Host Control](/assets/img/Dynamic.Wallpaper.minutes.png)

Legen Sie fest, wann die Funktion Dynamisches Hintergrund beenden werden soll:

![Host Control](/assets/img/Dynamic.Wallpaper.end.png)

!!! info "Hinweis"

    Das Aktivieren der Funktion Dynamisches Hintergrundbild wird nach einem Neustart des EZCast Pro Gerätes wirksam.