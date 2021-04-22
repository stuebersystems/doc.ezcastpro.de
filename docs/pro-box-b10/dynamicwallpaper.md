# Dynamisches Hintergrundbild

Was ist Dynamisches Hintergrundbild?

Mit Hilfe von dynamisches Hintergrundbild könnte die Startseite ihres EZCastpro Geräts sowohl mit Bildern als auch mit Video angepasst werden, zudem ermöglicht diese Funktion ebenso das Abspielen von bestimmten Bildern bzw. Video-Dateien direkt von EZCastpro Gerät auf dem Bildschirm ohne weiteres Endgerät zu benutzen.

## Wo findet man die Funktion „dynamisches Hintergrundbild“?

Um diese Funktion aufzufinden, benötigen Sie im EZCastpro App die „erweiterte Einstellungen“ aufrufen und sich als Admin anmelden

![Host Control](/assets/img/ezcastpro.II.select.adminsettings.png)

## Erweiterte Einstellungen aufrufen

Die Anmeldung kann per Erweiterte Einstellungen eines beliebigen End-Geräts durchgeführt werden. In diesem Beispiel zeigen wir Ihnen, wie die Anmeldung von einem Windows-PC vorgenommen wird.

* Um die Erweiterte Einstellungen zu erreichen, stellen Sie sicher, dass Sie die Software installiert haben und mit Ihrer EZCast Pro Gerät verbunden sind.
* Rufen Sie die Software EZCastPro auf Ihrem Gerät auf
* Wählen Sie Erweiterte Einstellungen unten links. 

## Anmeldung

* Geben Sie das Admin-Kennwort ein und klicken Sie auf OK, um sich anzumelden. Standardmäßig lautet das Kennwort 000000. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per Reset-Schalter zurück.
* Während der ersten Anmeldung, müssen Sie das Admin-Kennwort ändern. Danach müssen Sie sich noch einmal anmelden

Nach Anmeldung  wählen Sie die Option dynamisches Hintergrundbild und schalten Sie die ein.

![Host Control](/assets/img/dyn.hintergrund.ein.png)

* Anschließend können Sie der „Silent-Modus“ ein- oder ausschalten und die Leerlaufzeit der Aktivierung des dynamischen Hintergrunds festlegen.

Um die Video- und Bildinhalte auf dem Bildschirm abspielen zu lassen, ist die JSON-Datei erforderlich, die als URL oder als USB-Stick zugreifen könnte: 

![Host Control](/assets/img/URL.USBDISK.png)

* Bei URL wird nach Aktiviren der Funktion dynamisches Hintergrundbild die JSON-Datei automatisch vom Webserver zugreifen werden.
* Bei der Verwendung von USB-Stick soll der mit dem EZCast Pro Box angeschlossen sein, um die JSON-Datei von dem Stick zugreifen zu können.

![Host Control](/assets/img/URLlink.png)

* um die Video- und Bildinhalte zutreffend auf dem Bildschirm abspielen zu können, sollte die von Ihnen eingegebene Code mit dem unten abgebildeten Beispielcode übereinstimmen
* Bitte benennen die von Ihnen geschriebenen JSON- Datei als „wallpaper_file“. 

 ```` xml
{
   "slideshow": [
     
	
	  	                {
         "image_url": "http://assests.stueber.de/pictures/wallpapersden.com_london-city-bus_1920x1080.jpg",
                  "attribution": "london City",
         "duration": 10,
      },

	  	                {
         "image_url": "http://assests.stueber.de/pictures/wallpapersden.com_flower-sunflower-sky_1920x1080.jpg
                  "attribution": " sunflower",
         "duration": 10,
      },

        {
         "url": "http://1assests.stueber.de/videos/D10.introducing.de.mp4",
         "title": "Test video 1",
      },

	  	  	       
   ],
"next": ""
}
 ````



* In dem Code entspricht sich " image_url "- für Bilddatei und " url " – steht für Videoinhalten
* Beim Ausführen des Codes könnte auch den Titel und Dauer ein beliebiges Video und/ Oder Bilddatei bestimmt werden.
* Es wurde nur die MP4- für die Videoinhalten und JPG-formaten für die Bilddateien unterstützt. 

Sie können ihre JSON-Datei entweder auf webzugänglichen Server oder auf dem USB-Stick, um weitere Verwendung zu speichern. 

	
	
	
	
### Miracast

Das Protokoll Miracast unterstützt keinen vierstelligen Castcode, sondern einen achtstelligen Pincode, den Sie unter der Funktion [Erweiterte Einstellungen](adv.settings.md#Miracast) freischalten können:

![Host Control](/assets/img/Miracast.png)

Wenn ein Miracast-Gerät EZCast Pro einen Antrag zum Spiegeln sendet, taucht der achtstellige Pincode in gelb oben auf der Startseite auf. Diesen Pin muss man auf dem Endgerät eingeben, bevor die Bildschirmübertagung beginnen darf.

![Host Control](/assets/img/ProIIDongle_MiracastPin.png)

## Wie lege ich den Castcode fest?

Mit Hilfe der Funktion Erweiterte Einstellungen in der `EZCastPro` Software für [Windows und macOS](quickstart.md#InstallSoftware) oder in der App für [Android und iOS](quickstart.md#InstallApp) können Sie die Funktion Castcode einstellen.

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

### Castcode einstellen

* Aus dem Menü wählen Sie `Gerätemanagement` aus:

![](/assets/img/ezcastpro.II.select.devicemanagement.png)

* Wählen Sie den Menüpunkt `Castcode-Kontrolle` aus:

![](/assets/img/ezcastpro.II.devicemanagement.castcode.png)

* Wählen die gewünschte Einstellung aus:

![](/assets/img/ezcastpro.II.select.castcode.png)

* Um die Einstellung freizuschalten, müssen Sie die Pro Box II neustarten. Im Menü wählen Sie `Neustarten`.

![](/assets/img/prostickII_menu.neustart.png)

* Dann wählen Sie erneurt die Schaltfläche `Neustarten`.

![](/assets/img/restart.jpg)

