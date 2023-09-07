## Was genau wird deaktiviert?

Der EZCast Pro Stick II verfügt über zwei Netzwerkschnittstellen: 

* den [SoftAP](https://en.wikipedia.org/wiki/SoftAP), auch als **Direkte Verbindung** bekannt.
* die [Netzwerkinfrastruktur](connect.wifi.md), auch als **Über Router** bekannt.

Der SoftAP dient als intergrierter WLAN-AccessPoint des EZCast Pro Gerätes. Bei der Ersteinrichtung verbinden Sie Ihr Endgerät mit dem SoftAP. Anschließend verbinden Sie den EZCast Pro Stick II per WLAN mit Ihrer [Netzwerkinfrastruktur](connect.wifi.md). Das EZCast Pro Gerät ist dann standardmäßig über beide Netzwerkschnittstellen erreichbar:

![](/assets/img/softap.enabled.stick.png)

Wenn Sie also den SoftAP des EZCast Pro Gerätes deaktiveren, wird der Stick nur über die Netzwerkinfrastruktur erreichbar:

![](/assets/img/softap.disabled.stick.png)

### Betroffene Streamingprotokolle

Die folgenden Streamingprotokolle benötigen entweder eine Verbindung mit dem SoftAP oder mit der Netzwerkinfrastruktur:

* [AirPlay](airplay.md)
* [Google Cast](googlecast.md)
* [EZCast Pro App/Software](ezcastproapp.md)

### Nicht betroffene Streamingprotokolle

Das Streamingprotokoll [Miracast P2P](miracast.md#p2p-peer-to-peer) wird durch Deaktivieren des SoftAP nicht beeinträchtigt.

## Warum deaktiviert man den SoftAP?

* Sie möchten verhindern, dass Endgeräte unbeabsichtigt mit der falschen SSID erneut verbunden werden. Stattdessen sollten sie immer im Schul-WLAN verbleiben und über die Netzwerkinfrastruktur auf die EZCast Pro-Geräte zugreifen können.

* Sie möchten sicherstellen, dass alle Endgeräte sich zuerst über Ihre Netzwerkinfrastruktur authentifizieren, bevor sie auf das Internet oder andere Gerätedienste zugreifen können.

* Sie möchten die Anzahl der ausgestrahlten SSIDs in Ihrer Umgebung minimieren.

## Die zwei Miracast-Modi

Bevor Sie den SoftAP deaktivieren oder konfigurieren können, ist es wichtig, sich zunächst über die beiden Miracast-Modi mit EZCast Pro zu informieren.

Mit EZCast Pro II stehen zwei Miracast-Modi **Vollbildmodus (NGO-Modus)** und **Geteilter Bildschirm (AGO-Modus)** zur Verfügung. Diese beiden Modi bieten unterschiedliche Funktionalitäten und kontrollieren das Verhalten des SoftAP, einschließlich der Möglichkeit, ihn entweder vollständig zu deaktivieren oder nur das Kennwort zu verbergen. Wenn Sie sich noch nicht entschieden haben, welcher Miracast-Modus für Ihre EZCast Pro Geräte am besten passt, schauen Sie sich bitte einmal die umfassende Anleitung zur Verwendung beider [Miracast-Modi](miracast.md#miracast-modes).

Darum haben wir alle möglichen Optionen unter den entsprechenden Miracast-Modi unten zusammengefasst:

### Vollbildmodus (NGO-Modus)

Mithilfe der Funktion [Erweiterte Einstellungen](adv.settings.md) wählen Sie `Gerätemanagement` -> `Miracast` -> `Nur im Vollbildmodus` aus und starten Sie das EZCast Pro Gerät neu, um den Vollbildmodus (NGO-Modus) zu aktivieren:

![](/assets/img/Miracast.NGO.mode.png)

Nach Aktivierung des Vollbildmodus (NGO-Modus) stehen Ihnen folgende Optionen zur Verfügung:

#### SoftAP deaktivieren

* Mit der Einstellung `Admineinstellungen` -> `Verbindung` -> `Nur über Router` wird der SoftAP des EZCast Pro Gerätes vollständig deaktiviert:

![](/assets/img/connection.only-router.png)

Die SSID des SoftAP auf der Startseite wird ausgegraut. Das Kennwort und die IP-Adresse des SoftAP werden ausgeblendet. Die SSID des SoftAP wird nicht mehr ausgestrahlt und ist auf den Endgeräten nicht mehr sichtbar. Das EZCast Pro Gerät ist dann nur über Ihre Infrastruktur erreichbar:

![](/assets/img/ezcastpro.II.via.Router.only.png)

#### SSID ausblenden

Sie möchten den SoftAP nicht deaktivieren, sondern nur die SSID ausblenden? 

* Mit der Einstellung `Admineinstellungen` -> `Verbindung` -> `Über Router oder direkte Verbindung` wird der SoftAP aktiviert:

![](/assets/img/Connection_EZCastProII.png)

* Aktiveren Sie anschließend die Funktion `Gerätemanagement` -> `Gerätename` -> `SSID verstecken`:

![](/assets/img/hide.ssid.png)

Die SSID bzw. der Gerätename wird auf der Startseite ausgeblendet:

![](/assets/img/ssid.hidden.ngo-mode.png)

Eine Verbindung mit dem SoftAP muss auf dem Endgerät manuell eingestellt werden:

![](/assets/img/connect.hidden.ssid.png)

#### Kennwort ausblenden

Sie möchten den SoftAP nicht deaktivieren, sondern nur das Kennwort ausblenden? 

* Mit der Einstellung `Admineinstellungen` -> `Verbindung` -> `Über Router oder direkte Verbindung` wird der SoftAP aktiviert:

![](/assets/img/Connection_EZCastProII.png)

* Aktiveren Sie anschließend die Funktion `Netzwerkmanagement` -> `WLAN-Kennwort` -> `Kennwort verstecken`:

![](/assets/img/hide.password.png)

Das Kennwort wird auf der Startseite ausgeblendet:

![](/assets/img/password.hidden.ngo-mode.png)

### Geteilter Bildschirm (AGO-Modus)

Im AGO-Modus ist der SoftAP für den geteilten Bildschirm mit bis zu 4 Geräten, einschließlich Miracast, erforderlich. Die SSID des SoftAP kann weder deaktiviert noch ausgeblendet werden. Nur können Sie das Kennwort ausblenden:

#### Kennwort ausblenden

Da das Ausblenden des Kennworts nur im Vollbildmodus (NGO-Modus) aktiviert werden kann, schalten Sie zunächst auf diesen Modus um, indem Sie mithilfe der Funktion [Erweiterte Einstellungen](adv.settings.md) `Gerätemanagement` -> `Miracast` -> `Nur im Vollbildmodus` auswählen und das EZCast Pro Gerät neu starten:

![](/assets/img/Miracast.NGO.mode.png)

* Aktiveren Sie anschließend die Funktion `Netzwerkmanagement` -> `WLAN-Kennwort` -> `Kennwort verstecken`:

![](/assets/img/hide.password.png)

Wählen Sie zuletzt `Gerätemanagement` -> `Miracast` -> `Geteilter Bildschirm unterstützt` aus und starten Sie das EZCast Pro Gerät neu:

![](/assets/img/Miracast.AGO.mode2.png)

Das Kennwort wird auf der Startseite ausgeblendet und die angezeigte SSID bzw. der Gerätename enthält das Präfix `DIRECT-`:

![](/assets/img/password.hidden.ago-mode.png)

Eine umfassende Anleitung zu den beiden Schnittstellen finden Sie [hier](adv.settings.md#networkinterfaces).



