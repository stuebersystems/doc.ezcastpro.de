# Erweiterte Einstellungen

Mit der Funktion `Erweiterte Einstellungen` können Sie die Firmware aktualisieren und viele Einstellungen der EZCast Pro Box II bequem per Fernzugriff anpassen. Um die Erweiterte Einstellungen zu erreichen, stellen Sie sicher, dass Sie die [Software bzw. die App installiert haben](quickstart.md) und mit Ihrer EZCast Pro Box II verbunden sind.

Rufen Sie die Software bzw. die App `EZCastPro`auf Ihrem Gerät auf.

* Auf Windows/macOS wählen Sie `Erweiterte Einstellungen`.

![](/assets/img/Win-App-Advanced-Settings.png)

* Auf iOS/Android wählen Sie die Schaltfläche `Einstellungen` oben links, anschließend tippen Sie auf `Erweiterte`:

![](/assets/img/iOS_adv-settings.png)

## Anmeldung

Geben Sie das Admin-Kennwort ein und klicken Sie auf `OK`, um sich anzumelden. Standardmäßig lautet das Kennwort `000000`. Wenn dieses Kennwort nicht akzeptiert wird, setzen Sie das Gerät per [Reset-Schalter](reset.md#hardreset) zurück.

![](/assets/img/EZCastII_Login.png)

Während der ersten Anmeldung, müssen Sie das Admin-Kennwort ändern. Danach müssen Sie sich noch einmal anmelden.

![](/assets/img/new_password.png)

## Optionen des Hauptmenüs

Nach der Anmeldung erscheinen die folgenden Funktionen:

* [Verbundene Geräte](#connected-devices)
* [Konferenzsteuerung](#Konferenzsteuerung)
* [Gerätemanagement](#Geraetemanagement)
* [Netzwerkmanagement](#Netzwerkmanagement)
* [Admineinstellungen](#Admineinstellungen)
* [Neustarten](#restart)
* [Über das Gerät](#Ueber)

### Verbundene Geräte {#connected-devices}

Zeigt die verbundenen Nutzer und ihre zugewiesenen Rollen als entweder `Host` oder `Gast`. Weitere Informationen zum Thema Host und Gast finden Sie [hier](ezcastproapp.md#die-rollen---host-und-gast).

![](/assets/img/link-status.png)

### Konferenzsteuerung {#Konferenzsteuerung}

Mit der Konferenzensteuerung können Sie die folgenden Aufgaben durchführen:

* Alle Geräte trennen
* Die Role als Host bzw. als Moderator einem Gast zuordnen
* Geräte auf dem Bildschirm neu positionieren

![](/assets/img/Conference_Control.png)

Eine umfassende Information zu diesem Thema finden Sie [hier](conference-control.md). 

### Gerätemanagement {#Geraetemanagement}

Dieser Bereich hilft Ihnen, Einstellungen wie die [Sprache](#Sprache) der Benutzeroberfläche, die [Auflösung](#Auflösung) oder die Angabe [Max. Verbindungen](# MaxVerbindungen) zu wechseln.

#### Sprache {#Sprache}

Unter Sprache wählen die gewünschte Anzeigesprache des Menüs Erweiterte Einstellungen aus.

![](/assets/img/Select_language.jpg)

#### Gerätename bzw. SSID-Name {#Geraetename}

Hier können Sie den Gerätenamen ändern. Aus Sicherheitsgründen kann die SSID ausgeblendet bzw. deaktiviert werden.

![](/assets/img/ezcastpro.II.geraetename.png)

Die EZCast Pro Box II verfügt über drei Netzwerkschnittstellen. Beim Deaktivieren der SSID (wlan1) wird die Box nur über Router oder Miracast (P2P) erreichbar.

| wlan | Bemerkung |
| :------------- |:-----:|
| wlan0 | Router / AccessPoint |
| wlan1 | softAP (Direkte Verbindung) SSID/HotSpot |
| wlan2 | P2P, MiraCast |

#### Auflösung {#Auflösung}

Hier wählen Sie die Ausgabeauflösung der EZCast Pro Box II aus. Sie können entweder eine bestimmte Auflösung auswählen oder wählen Sie einfach `Auto` und die Pro Box II stellt die optimale Auslösung für Ihren Bildschirm automatisch ein.

| Standard | Auflösung|
| :------------- |:-----:|
| HD | 1280 × 720 |
| Full-HD | 1920 × 1080 |
| 4K UHD | 3840 × 2160 |
| DCI 4K | 4096 × 2160 |

Die folgenden Auflösungen können Sie festlegen:

![](/assets/img/ezcastpro.II.ausloesung.jpg)

#### Anzeigemodus {#Anzeigemodus}

Hier legen Sie fest, ob die Anzeige Ihres Endgeräts auf dem externen Bildschirm bzw. auf dem Beamer im `Original` oder im `Vollbild` angezeigt werden soll.

![](/assets/img/ezcastpro.II.anzeigemodus.png)

##### Original

Mit Original-Modus wird das ursprüngliche Seitenverhältnis des Endgeräts z.B. eines iPads auf dem externen Bildschirm bzw. auf dem Beamer angezeigt:

![Das iPad wird im Original angezeigt](/assets/img/NEC_E506_Original.png)

##### Vollbild

Mit Vollbild-Modus wird die Eingabe des Endgeräts automatisch angepasst, um das gleiche Seitenverhältnis wie der externe Bildschirm bzw. der Beamer zu haben:

![Das iPad wird im Vollbild angezeigt](/assets/img/NEC_E506_Vollbild.png)

#### AirPlay-Modus {#AirPlayMode}

Mit einem iOS/macOS Gerät können Sie Ihren Bildschirminhalt auch direkt per Apple AirPlay übertragen. Das bedeutet, Sie benötigen in diesem Fall keine EZCast Pro Software. Diese Funktion ist 'out-the-box' freigegeben. Eine umfassende Anleitung zur Verwendung von AirPlay finden Sie [hier](airplay.md).

Wählen Sie den Modus für Videowiedergabe aus:

* `Auto` - Automatischer Modus
* `Nur Bildschirm spiegeln` - Bildschirm und Video-Inhalte werden gespiegelt
* `Spiegeln + Video streamen` - Bildschirm wird gespiegelt und Online-Videos (z.B. YouTube) werden gestreamt

![](/assets/img/ezcastpro.II.EZAir_Mode.png)

#### AirView {#AirView}

AirView ein- oder ausschalten. Eine umfassende Anleitung zur Verwendung von AirView finden Sie [hier](ezcastproapp.md#airview).

![](/assets/img/AirView.png)

#### EZNote {#EZNote}

EZNote ein- oder ausschalten.

![](/assets/img/EZNote.png)

#### Castcode-Kontrolle {#Castcode}

Legen Sie fest, ob jeder Gast einen vierstelligen Code eingeben muss, um Inhalte übertragen zu dürfen.

* `AUS` - Kein Passcode wird benötigt
* `Zufällig` - Zufällig (erneut sich automatisch beim Einschalten bzw. beim Neustart)
* `Fest` - Einen festens Castcode angeben

Der Castcode wird hier angezeigt:

![Der Castcode](/assets/img/B10_Castcode.png)

Eine umfassende Anleitung zur Verwendung von Castcode finden Sie [hier](castcode.md).

#### Max. Verbindungen {#MaxVerbindungen}

Bei dieser Einstellung handelt es sich die maximale Zahl der direkten Verbindungen, die der EZCast Pro Stick II unterstützen soll. Zusätzlich werden noch 32 Verbindungen über Router unterstützt. 

Bitte beachten: Je größer jedoch die Anzahl der angeschlossenen Benutzer ist, desto geringer ist die Bandbreite für jeden Benutzer

![](/assets/img/ezcastpro.II.max.verbindungen.png)

#### Android Audioübertragung {#Android-Audio-Streaming}

Die Übertragung von Android-Ton über die Android-App unterstützen.

![](/assets/img/Android-Audio-Streaming.png)

#### ChromeCast {#Chromecast}

Die Übertragung von ChromeCast-Geräten unterstützen. Eine umfassende Anleitung zur Verwendung von Chromecast finden Sie [hier](chromecast.md).

![](/assets/img/Chromecast-support.png)

#### Miracast {#Miracast}

Die Übertragung von Miracast-Geräten unterstützen. Eine umfassende Anleitung zur Verwendung von Miracast finden Sie [hier](miracast.md).

![](/assets/img/Miracast.png)

#### Legacy-Modus (2,4 GHz WLAN) {#legacymode}

Um ältere Endgeräte bzw. nicht 5 GHz fähige Geräte zu unterstützen nutzen Sie diese Option, um die EZCast Pro Box II auf die 2,4 GHz-Band umzuschalten.

![](/assets/img/legacy.wifi.mode.png)

#### Zeitgesteuerter Neustart {#timedrestart}

Um die Leistung des EZCast Pro Gerätes zu optimieren, insbesondere bei Geräten, die dauerhaft im Betrieb sind, aktivieren Sie die Funktion `Zeitgesteurter Neustart`. Der Empfänger startet sich automatisch neu, wenn die folgenden Bedingungen zutreffen:

* Die EZCast Pro Box II war 2/4/8 Stunden nicht im Betrieb. 
* Kein Nutzer ist seit mind. 2/4/8 Stunden verbunden.
* Die Web-Oberfläche der Einstellungen wurde 2/4/8 Stunden nicht verwendet.

![Zeitgesteuerter Neustart einschalten](/assets/img/timed.restart.png)

### Netzwerkmanagement {#Netzwerkmanagement}

Im diesem Bereich können Sie Einstellungen zu dem Internet, IP-Einstellungen und WLAN-Kanal anpassen.

#### Mit 5GHz WLAN-Router/AP verbinden {#Internet}

Verbinden Sie die EZCast Pro Box mit Ihrem WLAN-Router.

**Bitte beachten:** Die EZCast Pro Box II kann nur mit einem `5GHz WLAN-Router` verbunden werden, es sei denn Sie haben den [Legacy-Modus (2,4 GHz WLAN)](#legacymode) freigeschaltet.

![](/assets/img/EZCastPro.II.Wifi.Internet.jpg)

#### WLAN merken {#Remember-WiFi}

Wenn die Verbindung von EZCast Pro Box II mit dem Internet bzw. mit Ihrem Router dauerhaft gemerkt werden soll, muss diese Option freigeschaltet sein. Wenn nicht, wird die Verbindung mit Ihrem Router nach einem Neustart der Box nicht automatisch wiederhergestellt.  

![](/assets/img/ezcastpro.II.remember.password.png)

#### WLAN IP-Einstellungen {#WLAN-IP-Einstellungen}

Weisen Sie der Pro Box II eine statische IP-Adresse zu oder setzen Sie automatische IP-Adressierung (DHCP).

![](/assets/img/static-IP.png)

#### WLAN-Kennwort ändern bzw. nicht sichtbar {#WLAN-Kennwort}

Legen Sie ein benutzerdefiniertes Kennwort für das WLAN der Pro Box fest und wählen Sie, ob das Kennwort aus Sicherheitsgründen ausgeblendet werden soll.

![](/assets/img/ezcastpro.II.kennwort.png)

#### WLAN-Kanal {#Wifi-Channel}

Um störende WLAN-Signale zu vermeiden, können Sie den WLAN-Modus anpassen.

![](/assets/img/ezcastpro.II.wifi.kanal.png)

### Admineinstellungen {#Admineinstellungen}

In diesem Bereich können Sie den EZCast Pro II Empfänger auf die neuste Firmware aktualisieren, auf Standardeinstellungen zurücksetzen und viele anderen erweiterten Einstellungen einsetzen.

#### Admin-Kennwort {#Admin-Kennwort}

Das Admin-Kennwort des Empfängers ändern.

![](/assets/img/new_password.png)

#### WLAN-Enterprise {#WiFi-Enterprise}

Ein digitales Zertifikat hochladen.

![](/assets/img/ezcastpro.II.digital_certificate.jpg)

#### Host-Berechtigungen {#Host-permissions}

Kontrollieren Sie, welche Funktionen der Host im Menü Erweiterte Einstellungen durchführen darf, ohne sich als `Admin` [anmelden](#anmeldung) zu müssen.

![Host-Berechtigungen](/assets/img/Host_permissions.png)

Möchten Sie bespielsweise, dass der Host keinen Zugang auf die Schaltfläche `Einstellungen` innerhalb der Software bzw. der App zugelassen wird, dann können Sie die Option `Gerätemanagement` auf `Aus` stellen.

![Host-Einstellungen können mit Hilfe der Host-Berechtigungen ausgeblendet werden](/assets/img/ezcastpro.II.software.no-hostsettings.jpg)

![Beim Ausschalten der Funktion Gerätemanagement wird die Schaltfläche Host-Einstellungen ausgeblendet](/assets/img/ezcastpro.II.software.hostsettings.hidden.png)

Bei der obigen Konfiguration (die Funktionen Gerätemanager-Steuerung und Netzwerksetup-Steuerung ausschalten) wird nur die Funktion `Konferenzsteuerung` und `Neustart` eingeblendet. Bitte beachten: Die Rubriken `Verbundene Geräte` und `Über das Gerät` stehen immer zur Verfügung.

![Funktion Konferenzensteuerung wird eingeblendet](/assets/img/ezcastpro.II.Host_authority_example.png)

#### Host-Kontrolle {#Host-Kontrolle}

Der erste Benutzer, der sich über die Software bzw. über die App verbindet, wird als Gastgeber (Host) bezeichnet und die anderen als Gäste. Standardmäßig muss jeden Antrag zum Senden vom Host genehmigt werden, im dem er mit entweder `Vollbild`, `Teilen`, oder `Ablehnen` antwortet: 

![](/assets/img/host.control_answer.png)

**Antrag automatisch genehmigen**

Wenn `Antrag automatisch genehmigen` auf `On` eingestellt ist, wird der Antrag zum Senden automatisch genehmigt.

**Bildschirm teilen**

Standardmäßig ist diese Funktion freigeschaltet. Dies bedeutet, dass der Bildschirm geteilt wird, um bis zu vier Geräte gleichzeitig zu zeigen, auch bekannt als Splitscreen-Modus. Wenn `Bildschirm teilen` aus ist, übernimmt der nächste genehmigte Sender im Vollbildmodus.

![](/assets/img/host.control.png)

Ein Status der Einstellungen der Host-Steuerung wird auf der Startseite unten angezeigt:

![](/assets/img/host.control_status.jpg)

#### Internetzugangskontrolle {#Internetzugangskontrolle}

Kontrollieren Sie, ob verbundene Geräte auf das Internet über den EZCast Pro II Empfänger zugreifen dürfen oder nicht. Standardmäßig werden alle Geräte erlaubt:

![](/assets/img/internet_access.png)

#### SNMP {#SNMP}

Schalten Sie SNMP V3 Unterstützung frei.

![](/assets/img/SNMP_support.jpg)

#### Mein Bildschirm {#Mein-Bildschirm}

Wenn gewünscht, kann man das Bild der Startseite austauschen. Dies ist eine dauerhafte Änderung. Nach dem Einspielen eines neuen Bildes kann das vorherige Bild nicht wiederhergestellt werden, auch bei einem [Zurücksetzen der Einstellungen](reset.md) der Box.

Einen Download der von uns mitgelieferten Startseite finden Sie [hier](https://download.stueber.de/doc/de/ezcastpro/EZCastProV2_StartseiteDE.png).

![](/assets/img/Mein_Bildschirm.png)

#### Dynamisches Hintergrundbild {#Dynamicwallpaper}

Das dynamische Hintergrundbild, ist eine Funktion, die nach einer einstellbaren Zeit der Inaktivität automatisch gestartet wird und eine Sammlung von Bildern bzw. Videos auf dem Bildschirm anzeigt.

Eine umfassende Anleitung zur Verwendung von Dynamisches Hintergrundbild finden Sie [hier](dynamicwallpaper.md).

#### OTA-Update-URL {#OTA-Server}

Einen OTA-Server angeben.

![](/assets/img/OTA_server.jpg)

#### Verbindung (Netzwerkschnittstellen) {#networkinterfaces}

Es gibt zwei Möglichkeiten, sich mit dem Empfänger zu verbinden. Bei der Ersteinrichtung der Box steht Ihnen standardmäßig die **Direkte Verbindung** zur Verfügung.

1.  **Direkte Verbindung**

    Sie verbinden Ihr Endgerät (Windows/Android/Apple/etc.) mit dem Hotspot des EZCast Pro Empfängers über die auf dem Bildschirm angezeigte SSID. Inhalte vom Internet werden im zweiten Schritt über die [Internetzugang-Funktion](internet.md) des Empfängers zu Ihrem Endgerät geliefert, wenn der Administrator dies freischaltet. Dies bietet im Prinzip die beste Bandbreite zwischen Ihrem Gerät und dem EZCast Pro Empfänger, wenn die Entfernung vom Netzwerk-Zugangspunkt sehr groß ist. Bei dieser Option muss der Benutzer vom bisherigen Netzwerk auf ein anderes Netzwerk d.h. die SSID des Empfängers wechseln.

    Die Zugangsdaten SSID u. Kennwort der direkten Verbindung werden oben angezeigt: 

    ![Die Zugangsdaten SSID u. Kennwort der direkten Verbindung werden oben angezeigt](/assets/img/ezcastpro.II.ssid_password.png)

    In der EZCast Pro Software wird eine verfügbare direkte Verbindung mit einem Symbol der Box rechts angezeigt: 

    ![In der EZCast Pro Software wird eine verfügbare direkte Verbindung mit einem Symbol der Box rechts angezeigt](/assets/img/ezcastpro.II.App.Direkte_Verbindung.png)

2.  **Über Router**

    Der EZCast Pro Empfänger wurde im Vorab vom Administrator per die [Internetzugang-Funktion](internet.md) des Empfängers mit Ihrem Router verbunden. Inhalte vom Internet werden im ersten Schritt von Ihrer Netzinfrastruktur zu Ihrem Gerät geliefert. Im zweiten Schritt verbinden Sie Ihr Endgerät (Windows/Android/Apple/etc.) mit dem EZCast Pro Empfänger. Bei dieser Option muss der Benutzer auf kein anderes Netzwerk wechseln.

    In der EZCast Pro Software wird eine verfügbare Verbindung über Router mit einem Symbol des Routers rechts angezeigt:
	
    ![In der EZCast Pro Software wird eine verfügbare Verbindung über Router mit einem Symbol des Routers rechts angezeigt](/assets/img/ezcastpro.II.App.connect.via.Router.png)

Standardmäßig werden beide Netzwerkschnittstellen durch die Einstellung `Über Router oder direkte Verbindung` freigeschaltet. Sie haben jedoch die Wahl, eine der Netzwerkschnittstellen zu deaktivieren:

![](/assets/img/Connection_EZCastProII.png)

Mit den ersten zwei Optionen `Über Router oder direkte Verbindung` sowie mit `Nur direkte Verbindung` werden die SSID und das Kennwort dazu auf der Startseite angezeigt, wie unten abgebildet:

![](/assets/img/B10_landingpage.png)

Mit `Nur über Router` wird der Access-Point der EZCast Pro Box II  ausgeschaltet und Sie können nur über Ihren Router mit der Box verbinden. Die SSID und das Kennwort werden ausgegraut und die vom Router vergebenen IP-Adresse bzw. die statische IP-Adresse der Box wird auf der Startseite angezeigt (unten links), wie unten abgebildet:

![](/assets/img/ezcastpro.II.via.Router.only.png)

!!! warning "Achtung"

    Bitte beachten Sie, dass die Freischaltung der Option `Nur direkte Verbindung` oder `Nur über Router` dazu führt, dass Verbindungen über den anderen Modus nicht mehr möglich sind. Wenn Sie `nur direkt Verbindung` sowie [SSID nicht sichtbar](#Geraetename) oder [Kennwort nicht sichtbar](#WIFI-Kennwort) freigeschalten, dürfen Sie die Zugangsdaten nicht vergessen, sonst müssten Sie ein [Zurücksetzen per Reset-Schalter](reset.md#hardreset) durchführen!

#### Festgelegter Host {#Fixedhost}

Legen Sie einen bestimmten Benutzer fest, dass sich immer als Host der Präsentation innerhalb der Software bzw. der App bezeichnet wird. Weitere Informationen zu diesem Thema finden Sie [hier](fixedhost.md).

![](/assets/img/ProIIStick_Fixedhost.Select.png)

#### Upgrade (Firmware) {#Aktualisieren}

Sie können die Firmware der EZCast Pro II Box aktualisieren, um die neuesten Erweiterungen und Funktionen nutzen zu können.

![](/assets/img/Update.jpg)

Klicken Sie [hier](firmware-upgrade.md) für eine vollständige Anleitung zum Aktualisieren der Firmware.

#### Auf Standardeinstellungen zurücksetzen {#Reset}

Nutzen Sie diese Option, um die Pro Box auf die Standardeinstellungen zurückzusetzen. Weitere Informationen dazu finden Sie [hier](reset.md).

![](/assets/img/Reset.png)

### Neustarten {#restart}

Nutzen Sie diese Option, um die Pro Box neu zu starten.

![](/assets/img/restart.jpg)

### Über das Gerät {#Ueber}

Nutzen Sie diese Option, um eine Übersicht der Pro Box z.B. Firmware-Version, IP-Adresse sowie Daten zum WLAN zu erhalten.

![](/assets/img/D10.about_stick.png)