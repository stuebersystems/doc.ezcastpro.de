# Erweiterte Einstellungen

Mit der Funktion Erweiterte Einstellungen können Sie die Firmware aktualisieren und viele Einstellungen der EZCast Pro LAN Box I bequem per Fernzugriff anpassen. Um die Erweiterte Einstellungen zu erreichen, stellen Sie sicher, dass Sie die [Software bzw. die App installiert haben](quickstart.md) und mit der Box verbunden sind.

Rufen Sie die Software bzw. die App `EZCastPro`auf Ihrem Gerät auf.

* Auf Windows/macOS wählen Sie `Erweiterte Einstellungen`.

![](/assets/img/Win-App-Advanced-Settings.png)

* Auf iOS/Android wählen Sie die Schaltfläche `Einstellungen` oben links, anschließend tippen Sie auf `Erweiterte`:

![](/assets/img/iOS_adv-settings.png)

## Anmeldung

* Wählen Sie die Schaltfläche `Login` oben rechts, um sich anzumelden.

![](/assets/img/EZCast_Login.jpg)

* Standardmäßig lautet das Kennwort `000000` oder `Connect4`. Wenn dieses Kennwort nicht akzeptiert wird, können Sie ein neues Kennwort direkt [hier](https://www.ezcast.com/service/product/support) oder über die E-Mail [forgetpassword@iezvu.com](mailto:forgetpassword@iezvu.com) anfordern.

![](/assets/img/EZCast_Enter-Password.jpg)

* Während der ersten Anmeldung, müssen Sie das Admin-Kennwort ändern. Danach müssen Sie sich noch einmal anmelden.

![](/assets/img/new_password.png)

* Um das Menü aufzuklappen, klicken Sie auf das Menü-Symbol oben links.

![](/assets/img/menu_button.jpg)

* Sechs Funktionen Status des Links, [Konferenzensteuerung](#Konferenzensteuerung), [Gerätemanagement](#Geraetemanagement), [Netzwerkmanagement](#Netzwerkmanagement), Admin-Einstellungen, und Reboot-Steuerung erscheinen. Unter [Über](#Ueber) sind Informationen zu der Firmware-Version, IP-Adresse sowie Daten zum WLAN zu finden.

![](/assets/img/prostick_menu.jpg)

## Konferenzensteuerung {#Konferenzensteuerung}

Mit der Konferenzensteuerung können Sie die folgenden Aufgaben durchführen:

* Alle Geräte trennen
* Die Role als Host bzw. als Moderator einem Gast zuordnen
* Geräte auf dem Bildschirm neu positionieren

![](/assets/img/Conference_Control.png)

## Gerätemanagement {#Geraetemanagement}

Dieser Bereich hilft Ihnen, die [Sprache](#Sprache) der Benutzeroberfläche, die [Auflösung](#Auflösung) oder die Angabe [Max. Verbindungen](#MaxVerbindungen) zu wechseln.

![](/assets/img/Device_Management.jpg)

### Sprache {#Sprache}

Unter Sprache wählen die gewünschte Anzeigesprache des Menüs Erweiterte Einstellungen aus.

![](/assets/img/Select_language.jpg)

### Gerätename (umbenennen) {#Geraetename}

Hier können Sie den Gerätenamen ändern

![](/assets/img/device_name.jpg)

### Auflösung {#Auflösung}

Hier wählen Sie die Ausgabeauflösung der Pro Box aus.

![](/assets/img/prostick_resolution.jpg)

### EZAir Mode {#EZAirMode}

Wählen Sie den Modus für Videowiedergabe.

![](/assets/img/EZAir_Mode.jpg)

### Max. Verbindungen {#MaxVerbindungen}

Hier geben Sie die maximale Benutzeranzahl des Empfängers an.

![](/assets/img/Max_connections.jpg)

### Castcode-Kontrolle {#Castcode-Kontrolle}

Legen Sie fest, ob jeder Gast einen vierstelligen Code eingeben muss, um Inhalte übertragen zu dürfen.

![](/assets/img/castcode_control.jpg)

### AirView {#AirView}

AirDisk ein- oder ausschalten.

![](/assets/img/AirView.png)

## Netzwerkmanagement {#Netzwerkmanagement}

Im diesem Bereich können Sie Einstellungen zu dem Internet,  IP-Einstellungen und WLAN-Zugangsdaten anpassen. 

![](/assets/img/Network_Management.jpg)

### Internet {#Internet}

Verbinden Sie die Pro Box mit Ihrem WLAN-Router.

![](/assets/img/EZCast_Wifi_Internet.jpg)

### WiFi IP-Einstellungen {#WiFi-IP-Einstellungen}

Weisen Sie der Pro Box eine statische IP-Adresse zu oder setzen Sie automatische IP-Adressierung (DHCP).

![](/assets/img/static-IP.png)

### WIFI-Kennwort {#WIFI-Kennwort}

Legen Sie ein benutzerdefiniertes Kennwort für das WLAN der Pro Box.

![](/assets/img/Kennwort.jpg)

### WIFI-SSID (umbenennen) {#WIFI-SSID}

Hier können Sie die SSID des Empfängers umbenennen.

![](/assets/img/SSID_Name.jpg)

### Kennwort nicht sichtbar {#HidePassword}

Aus Sicherheitsgründen kann das Kennwort ausgeblendet werden.

![](/assets/img/hide_password.jpg)

### Wifi-Kanal {#Wifi-Channel}

Um störende WLAN-Signale zu vermeiden, können Sie den WLAN-Modus anpassen.

![](/assets/img/wifi_channel_settings.jpg)

## Admin-Einstellungen {#Admineinstellungen}

In diesem Bereich können Sie den EZCast Pro Empfänger auf die neueste Firmware aktualisieren, auf Standardeinstellungen zurücksetzen und andere erweiterten Einstellungen setzen.

![](/assets/img/Admin-Einstellungen.jpg)

### Admin-Kennwort {#Admin-Kennwort}

Das Admin-Kennwort des Empfängers ändern.

![](/assets/img/new_password.png)

### WiFi-Enterprise {#WiFi-Enterprise}

Ein digitales Zertifikat hochladen.

![](/assets/img/digital_certificate.png)

### Host-Autorität {#Host-Authority}

Kontrollieren Sie, welche Funktionen der Host im Menü Erweiterte Einstellungen durchführen darf, ohne sich als `Admin` [anmelden](#anmeldung) zu müssen.

![Host-Berechtigungen](/assets/img/Host_permissions.png)

Bei der obigen Konfiguration wird beispielsweise nur die Funktion `Konferenzensteuerung` eingeblendet. Bitte beachten Sie: Die Rubriken `Status des Links` und `Über` stehen immer zur Verfügung.

![Funktion Konferenzensteuerung per Host-Autorität einblenden](/assets/img/Host_authority_example.jpg)

### Internetzugangskontrolle {#Internetzugangskontrolle}

Kontrollieren Sie, ob verbundene Geräte auf das Internet über den EZCast Pro Empfänger zugreifen dürfen oder nicht. Standardmäßig werden alle Geräte erlaubt:

![](/assets/img/internet_access.png)

### SNMP {#SNMP}

Schalten Sie SNMP V3 Unterstützung frei.

![](/assets/img/SNMP_support.jpg)

### OTA-Server {#OTA-Server}

Einen OTA-Server angeben.

![](/assets/img/OTA_server.jpg)

### Verbindung (Netzwerkschnittstellen) {#networkinterfaces}

Es gibt zwei Möglichkeiten, sich mit dem Empfänger zu verbinden:

*  **Direkte Verbindung**

    Sie verbinden Ihr Gerät (Windows/Android/Apple/etc.) mit dem EZCast Pro Empfänger über die auf dem Bildschirm angezeigte SSID. Dies wird auch als `Peer-to-Peer` bezeichnet. Inhalte vom Internet werden im zweiten Schritt über die [Internetzugang-Funktion](internet.md) des Empfängers zu Ihrem Gerät geliefert, wenn der Administrator dies freischaltet. Dies bietet im Prinzip die beste Bandbreite zwischen Ihrem Gerät und dem EZCast Pro Empfänger, wenn die Entfernung vom Netzwerk-Zugangspunkt sehr groß ist. Bei dieser Option muss der Benutzer vom bisherigen Netzwerk auf ein anderes Netzwerk d.h. die SSID des Empfängers wechseln.

*  **Über Router**

    Der EZCast Pro Empfänger wurde im Vorab vom Administrator über die [Internetzugang-Funktion](internet.md) des Empfängers mit Ihrem Router verbunden. Inhalte vom Internet werden im ersten Schritt vom Ihrer Netzinfrastruktur zu Ihrem Gerät geliefert. Im zweiten Schritt verbinden Sie Ihr Gerät (Windows/Android/Apple/etc.) mit dem EZCast Pro Empfänger. Bei dieser Option muss der Benutzer auf kein anderes Netzwerk wechseln.

Standardmäßig werden beide Netzwerkschnittstellen durch die Einstellung `Über Router oder direkte Verbindung` freigeschaltet. Sie haben jedoch die Wahl, eine der Netzwerkschnittstellen zu deaktivieren:

![](/assets/img/Connection.jpg)

Mit `Über Router oder direkte Verbindung` werden die SSID, das Kennwort dazu, der Gerätename sowie die vom Router vergebenen IP-Adresse (oder die statische IP-Adresse) des Empfängers auf der Startseite angezeigt, wie unten abgebildet:

![](/assets/img/Via_Router_or_Direct-Link.jpg)

Mit `Nur direkte Verbindung` werden die SSID und das Kennwort dazu auf der Startseite angezeigt, wie unten abgebildet:

![](/assets/img/Direct_Link_Only.jpg)

Mit `Nur über Router` wird der Access-Point der EZCast Pro Box ausgeschaltet und Sie können nur über Ihren Router mit der Box verbinden. Der Gerätename des Empfängers sowie die vom Router vergebenen IP-Adresse (oder die statische IP-Adresse) des Empfängers auf der Startseite angezeigt, wie unten abgebildet:

![](/assets/img/Router_Only.jpg)

!!! warning "Achtung"
    
	Bitte beachten Sie, dass die Freischaltung der Option `Nur direkte Verbindung` oder `Nur über Router` dazu führt, dass Verbindungen über den anderen Modus nicht mehr möglich ist. Wenn Sie "nur direkte Verbindung" sowie [SSID nicht sichtbar](#HideSSID) oder [Kennwort nicht sichtbar](#HidePassword) freigeschalten dürfen Sie die Zugangsdaten nicht vergessen!

### SSID nicht sichtbar {#HideSSID}

Aus Sicherheitsgründen kann die SSID nicht sichtbar werden.

![](/assets/img/Hide_SSID.jpg)

### Aktualisieren {#Aktualisieren}

Sie können die Firmware des Empfängers aktualisieren, um die neuesten Erweiterungen und Funktionen nutzen zu können.

![](/assets/img/Update.jpg)

### Standardeinstellungen zurücksetzen {#Reset}

Nutzen Sie diese Option, um die Pro Box auf die Standard-Einstellungen zurückzusetzen. Weitere Informationen dazu finden Sie [hier](reset.md).

![](/assets/img/Reset.png)

## Über {#Ueber}

Nutzen Sie diese Option, um eine Übersicht der Pro Box zu erhalten.

![Über](/assets/img/about_stick.jpg)