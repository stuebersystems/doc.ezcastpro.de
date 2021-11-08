# Castcode festlegen

Der Castcode gewährleistet zusätzliche Sicherheit gegen unberechtigte Bildschirmübertragung, indem jeder Gast einen vierstelligen Code eingeben muss, um Inhalte übertragen zu dürfen. So können Sie sicherstellen, dass nur Teilnehmer Inhalte übertragen, die im gleichem Raum sind. Die folgenden Einstellungen stehen zur Verfügung:

* `AUS` - Kein Castcode wird benötigt
* `Zufällig` - Zufällig (erneut sich automatisch beim Einschalten bzw. beim Neustart)
* `Fest` - Einen festens Castcode angeben

Der Castcode wird oben mitten der Startseite angezeigt:

![Der Castcode](/assets/img/B10_Castcode.png)

Das Endgerät gibt den Castcode ein, dann darf die Bildschirmübertragung beginnen:

![Der Castcode](/assets/img/Enddevice_MiracastPin.png)

## Welche Streamingprotokolle unterstützt der Castcode?

Der Castcode wird bei einem Antrag zum Senden von folgenden Streamingprotokolle bzw. Anwendungen angefordert:

* Die EZCast Pro Software für Windows und macOS
* Die EZCast Pro App für Android und iOS
* AirPlay auf iOS und macOS

## Welche Streamingprotokolle unterstützt der Castcode nicht?

Aufgrund einer Limitierung der Protokollen kann der Castcode unter folgenden Streamingprotokolle nicht unterstützt werden. Trotzdem können Sie sich gegen unberechtigte Bildschirmübertragung schützen:

* Google Cast
* Miracast

### Google Cast

Derzeit gibt es innerhalb des Protokolls Chromecast keine Castcode-Funktionalität. Sie haben jedoch die Möglichkeit mit Hilfe der EZCast Pro App/Software die Funktion Host-Kontrolle gegen unberechtigte Bildschirmübertragung zu schützen. Wenn ein Chromecast Gerät versucht zu übertragen, müsste der Antrag zum Senden vom Moderator (Host) genehmigt werden:

![Host Control](/assets/img/AppHostKontrolle.png)

Weitere Informationen zum Thema Host-Kontrolle finden Sie [hier](ezcastproapp.md#host-kontrolle)

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

* Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#hardreset) zurück.

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

* Dann wählen Sie erneut die Schaltfläche `Neustarten`.

![](/assets/img/restart.jpg)

