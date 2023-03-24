# Sicherheitscodes aktivieren

## Was ist ein Sicherheitscode?

Ein Sicherheitscode gewährleistet zusätzliche Sicherheit gegen unberechtigte Bildschirmübertragung, indem jeder Teilnehmer einen Code eingeben muss, bevor die Bildschirmübertagung beginnen darf. So können Sie sicherstellen, dass nur die im Raum anwesenden Personen ihre Inhalte anzeigen können. 

![Der Castcode](/assets/img/enter.castcode.png)

EZCast Pro integriert verschiedene Streamingprotokolle (Miracast/AirPlay/Google Cast), um alle Endgeräte nach dem Prinzip Bring Your Own Device (BYOD) unterstützen zu können. Jedes Streamingprotokoll enthält seine eigene entwickelte Funktionalität.

## Welche Streamingprotokolle unterstützen einen Sicherheitscode?

Ein Sicherheitscode wird mit den folgenden Streamingprotokollen unterstützt:

* Die `EZCast Pro Software` unter Windows und macOS
* Die `EZCast Pro App` unter Android und iOS
* `AirPlay` unter iOS und macOS
* `Miracast` unter Windows und Android

## Wie unterscheiden sich die Sicherheitscodes der Streamingprotokolle?

### Castcode

Der Castcode wurde von EZCast Pro entwickelt und unterstützt das Protokoll `AirPlay` sowie alle Geräte, die `EZCast Pro Software/App` verwenden. Es handelt sich um einen vierstelligen Code, der oben mitten der Startseite ständig angezeigt wird:

![Der Castcode](/assets/img/B10_Castcode.png)

Die Funktion `Castcode-Kontrolle` ist in der Weboberfläche unter [Gerätemanagement -> Castcode-Kontrolle](adv.settings.md#Castcode) zu finden und bietet folgende Einstellungen:

* `AUS` - Kein Castcode wird benötigt bzw. angezeigt.
* `Zufällig` - Erneut sich regelmäßig
* `Fest` - Einen festen Castcode angeben

### Miracast PIN 

Der Miracast-PIN erscheint erst als zufälliger vierstelliger oder achtstelliger Code in gelb oben auf der Startseite, wenn ein Miracast-Gerät dem EZCast Pro Gerät einen Antrag zum Spiegeln sendet:

![Miracast PIN ](/assets/img/ProIIDongle_MiracastPin.png)
 
Aktivieren Sie den Miracast-PIN in der Weboberfläche unter [Gerätemanagement -> Miracast](adv.settings.md#Miracast) und wählen Sie den gewünschten PIN-Modus aus:

![Miracast PIN ](/assets/img/Miracast.pin.AGO.mode.png)

Standardmäßig wird der Miracast-PIN nur beim erstem Mal angefordert. Ab der Firmware [1.17478.20](whatsnew.md#ezcast-pro-stick-ii-firmware-11747820) kann man die Funktion `PIN immer anfordern` einstellen. Diese Option steht allerdings nur im Modus **Nur im Vollbildmodus** zur Verfügung. Klicken Sie [hier](miracast.md#die-zwei-miracast-modi), um mehr über die zwei verschiedende Modi **Nur im Vollbildmodus** und **Geteilter Bildschirm** zu erfahren:

![Miracast PIN ](/assets/img/Miracast.pin.NGO.mode.png)

### AirPlay PIN

Viele Organisationen, Schulen und Unternehmen nutzen [Mobile Device Management](https://support.apple.com/de-de/guide/deployment-education/edu1c1be3511/web) (MDM), um ihre Geräte zu verwalten. Je nach den Richtlinien Ihrer Organisation kann es erfordlich sein, den AirPlay-PIN zu aktivieren, um den Bildschirm Ihres Apple-Gerätes übertragen zu können.

Der AirPlay-PIN-Code erscheint erst als zufälliger vierstelliger Code unten auf der Startseite, wenn ein Apple-Gerät dem EZCast Pro Gerät einen Antrag zum Spiegeln sendet:

![AirPlay PIN](/assets/img/airplay.pin.png)
 
Aktivieren Sie den AirPlay-PIN-Code in der Weboberfläche unter [Gerätemanagement -> AirPlay-Modus](adv.settings.md#AirPlayMode):

![AirPlay PIN](/assets/img/ezcastpro.II.AirPlay.Settings.activate.png)

## Welche Streamingprotokolle unterstützen keinen Sicherheitscode?

Aufgrund einer Limitierung des Protokolls unterstützt `Google Cast` aktuell keinen Sicherheitscode. Sie können dennoch gegen unberechtigte Bildschirmübertragung schützen:

### Google Cast

Derzeit gibt es innerhalb des Protokolls `Google Cast` keinen Sicherheitscode. Sie haben jedoch die Möglichkeit mit Hilfe der EZCast Pro App/Software die Funktion Host-Kontrolle gegen unberechtigte Bildschirmübertragung zu schützen. Wenn ein Gerät  versucht über Google Cast zu übertragen, muss der Antrag zum Senden vom Moderator (Host) genehmigt werden:

![Host Control](/assets/img/AppHostKontrolle.png)

Weitere Informationen zum Thema Host-Kontrolle finden Sie [hier](ezcastproapp.md#hostcontrol)

Wenn Sie nur Streamingprotokolle zulassen möchten, die einen Sicherheitscode unterstützen, können Sie das Protokoll Google Cast unter [Gerätemanagement -> Google Cast](adv.settings.md#googlecast) deaktivieren:

![Host Control](/assets/img/googlecast.deactivate.png)

## Wie genau aktiviert man einen Sicherheitscode?

### Erweiterte Einstellungen öffnen

* Verbinden Sie Ihr Endgerät mit dem EZCast Pro II Gerät, entweder mit der SSID des EZCast Pro II Gerätes oder mit derselben WLAN- bzw. LAN-Infrastruktur, mit welcher das EZCast Pro II Gerät verbunden ist:

![](/assets/img/proII.network.connect.png)

* Geben Sie die IP-Adresse Ihres EZCast Pro Gerätes in einem beliebigen Webbrowser ein, die unten links auf der Startseite angezeigt wird:

![](/assets/img/proII_IP.connect.png)

### Sich als Admin anmelden

* Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird setzen Sie das Gerät per [Reset-Schalter](reset.md#hardreset) zurück.

![](/assets/img/EZCastII_Login.png)

* Während der ersten Anmeldung, müssen Sie das Admin-Kennwort ändern. Danach müssen Sie sich noch einmal anmelden.

![](/assets/img/new_password.png)

### Einen Sicherheitscode aktivieren

* Zum Aktivieren des **Castcodes**, wählen Sie [Gerätemanagement -> Castcode-Kontrolle](adv.settings.md#Castcode):

![](/assets/img/ezcastpro.II.devicemanagement.castcode.png)

* Wählen Sie die gewünschte Einstellung aus:

![](/assets/img/ezcastpro.II.select.castcode.png)

* Zum Aktivieren des **Miracast-PINs**, wählen Sie [Gerätemanagement -> Miracast](adv.settings.md#Miracast):

![Miracast PIN ](/assets/img/Miracast.pin.png)

* Zum Aktivieren des **AirPlay-PINs** wählen Sie [Gerätemanagement -> AirPlay-Modus](adv.settings.md#AirPlayMode):

![AirPlay PIN](/assets/img/ezcastpro.II.AirPlay.Settings.activate.png)

* Um die Einstellung freizuschalten, muss das EZCast Pro Gerät neu gestartet werden. Im Hauptmenü wählen Sie `Neustarten`.

![](/assets/img/prostickII_menu.neustart.png)

* Dann wählen Sie erneut die Schaltfläche `Neustarten`.

![](/assets/img/restart.jpg)

