# Was tun bei Stabilitätsproblemen?

Sie haben entweder von Anfang an Probleme mit Unterbrechungen der kabellosen Bildschirmübertragung, oder die Geräte haben anfangs einwandfrei funktioniert und nun merken Sie, dass die Bildschirmübertragung nach einer gewissen Zeit abbricht.

Dies kann verschiedene Ursachen und somit unterschiedliche Lösungen haben. Es handelt sich um WLAN-Geräte, die einen Videostream von einem Endgerät über eine drahtlose Verbindung mit möglichst wenigen Hindernissen zu einem Beamer oder Display übertragen, sogar durch eine Access-Point/Router-Infrastruktur hindurch. Darüber hinaus muss das Gerät über einen USB-Anschluss mit Strom versorgt werden.

!!! tip "Hinweis"
    
	Wenn einer dieser Punkte nicht optimal eingerichtet ist, kann dies zu Unterbrechungen und einer schlechten Leistung führen.

## Checkliste

Überprüfen Sie bitte sorgfältig alle Hilfspunkte der unterstehenden Checklist. Die ersten vier Punkte sind entscheidend und beeinflussen die Stabilität und Leistung des EZCast Pro Stick II erheblich:

### 1. Stromversorgung prüfen

Auch wenn es intuitiv erscheinen mag, den Stick über einen beliebigen USB-Anschluss des Projektors mit Strom zu versorgen, ist große Vorsicht geboten. Ohne eine ausreichende Stromversorgung über den angeschlossenen USB-A-Anschluss, der den **Mindeststrom 7,5W (5V/1,5A)** liefert, lässt sich der Stick zwar einschalten, wird aber zu Abbrüchen führen. Wenn Ihre Anzeige über keinen USB-Ladeanschluss verfügt, oder bestehen Zweifel, ob der USB-Ladeanschluss den Mindeststrom unterstützt, bitten wir Sie ein [USB-Ladegerät (5V/2A)](setup-tipps.md#samsung.powersupply) zu benutzen:

**Falsche Stromversorgung vom Beamer**

![image.png](/assets/img/D10-1xPlug-InternalPower.500ma.png)

**Richtige Stromversorgung vom Beamer**

![image.png](/assets/img/D10-1xPlug-InternalPower.5V2A.png)

**Richtige Stromversorgung mit USB-Netzteil (5V/2A)**

![image.png](/assets/img/D10-2xPlugs-ExternalPower.png)

Schauen Sie sich bitte unsere [Hinweise zur Stromversorgung](https://doc.ezcastpro.de/pro-stick-d10/setup.projector/#power).

### 2. Einrichtung prüfen

Fehlt eventuell die mitgelieferte HDMI-Verlängerung in der Einrichtung? Oder der Stick wurde fälschlicherweise hinter dem Bildschirm montiert?

Schauen Sie sich bitte unsere empfohlene Einrichtungen zusammen mit einem **Projektor** und mit einem **Large Display** an:

#### Projektor

* [Empfohlene Einrichtigungen](setup.projector.md)

* [Falsche Einrichtungen](setup.projector.md#falsche-einrichtungen)

![image.png](/assets/img/D10.projector.thumbnail.png)

#### Large Display

* [Empfohlene Einrichtigungen](setup.large.display.md)

* [Falsche Einrichtungen](setup.large.display.md#falsche-einrichtungen)

![image.png](/assets/img/D10.large.screen.20cm.thumbnail.png)

### 3. Firmware prüfen

#### Firmwareversion

Läuft die [neueste Firmware](whatsnew.md) auf dem Gerät? Sie können die Firmware entweder über WLAN [aktualisieren](firmware-reinstall.md) oder per USB-Kabel neu installieren.

#### Empfohlene Einstellungen 

Schauen Sie sich bitte anschließend unsere [empfohlene Einstellungen](reset.md#recommendedsettings) an:

### 4. WLAN überprüfen

Lesen Sie bitte sorgfältig die [Voraussetzungen](connect.wifi.md#voraussetzungen) für die Verbindung mit einem WLAN:

Folgende sind die häufigsten Fehler:

* **Verbinden Sie nicht mit einer Dual-Band 2,4Ghz/5Ghz SSID**. Nutzen Sie stattdessen eine dedizierte SSID, die auf den [5GHz-Bereich](https://en.wikipedia.org/wiki/List_of_WLAN_channels#5_GHz_(802.11a/h/j/n/ac/ax)) (20Mhz-Kanäle 36,40,44,48) beschränkt ist. Benutzen Sie bitte nicht [DFS-Kanäle](https://en.wikipedia.org/wiki/Dynamic_frequency_selection), um Abbrüche durch plötzlichen Kanalwechsel während der Bildschirmübertragung zu vermeiden.

* Halten Sie den Abstand zwischen dem EZCast Pro Stick II und dem Access Point sowie den Endgeräten auf maximal 10 Meter. Achten Sie dabei auf eine optimale Signalstärke zwischen -40 dBm und -50 dBm.

### 5. WLAN-Umgebung scannen und RSSI prüfen

Es handelt sich um zwei wichtige Tests der Signalstärke, auch bekannt als RSSI (Received Signal Strength Indicator in englisher Sprache). Dies ist eine wichtige Messgrösse, wenn es um die WLAN-Leistung geht.

Eine umfassende Anleitung zum Scannen Ihrer WLAN-Umgebug finden Sie [hier](wifi.environment.md).

### 6. Debug Logdatei zusenden

Von demselben Stick (siehe Punkt 5.), den Sie in der selben WLAN-Umgebung im Schritt 5 geprüft haben, lassen Sie uns bitte eine [Debug-Logdatei](logfile.md#download.logfile) des Sticks zukommen.

### 7. Anschlüsse Iher WLAN-Infrastuktur prüfen 

Haben Sie Konnektivitätsprobleme mit bestimmten Funktionen? Prüfen Sie bitte Ihre WLAN-Infrastuktur, ob alle erforderlichen [Anschlüsse für EZCast Pro](../ports.md) zugelassen sind: