# Was ist Captive Portal?

Ein Captive Portal präsentiert dem Benutzer eine Anmeldeseite, die sich nach der Erstverbindung mit dem WLAN automatisch öffnet. Er muss die Nutzungsbedingungen akzeptieren, bevor er auf das WLAN-Netzwerk der Schule bzw. des Unternehmens zugreifen darf. In manchen Fällen kann das Captive Portal einen Benutzernamen und ein Kennwort erfordern. Die Verwendung eines Captive Portals gibt einer Schule bzw. einem Hotel erhöhte Kontrolle über ihre Bandbreite und bietet gleichzeitig individuell anpassbare Grenzen dafür, wie lange Benutzer mit Ihrem Netzwerk verbunden bleiben können.

![Captive Portal im Einsatz in einer Schule](/assets/img/captiveportal.login.png)

## Kann der EZCast Pro sich in einem Captive Portal anmelden?

Da ein Captive Portal ein manuelles Eingeben der Zugangsdaten benötigt, kann EZCast Pro sich nicht in einem Captive Portal anmelden. Jedoch, es ist möglich EZCast Pro in Ihre Infrastruktur zu integrieren, in dem Sie eine `MAC-Authentifizierung` als eine Ausnahme auf Ihrem Router bzw. auf Ihrer Firewall erstellen, damit dieser Schritt entfällt.

Die MAC-Adresse der EZCast Pro Box II ist im Rubrik `Über das Gerät` in der Funktion [Erweiterte Einstellungen](adv.settings.md) zu finden:

![MAC-Adresse im Rubrik Über](/assets/img/D10.About.MAC.png)

Eine MAC-Adresse ist die bessere Wahl als die Verwendung einer IP-Adresse, da sich die MAC-Adresse nicht ändert. Bitte wenden Sie sich an Ihre IT-Abteilung, um die MAC-Adresse der EZCast Pro Box II zuzulassen.

## Die Direkte Verbindung deaktivieren

Es gibt anschließend eine mögliche Sicherheitslücke, die Sie leicht überwinden können:

Damit die EZCast Pro Box II den Nutzern keinen Zugang zu Ihrem Netzwerk ermöglicht, ohne sich erst über das Captive Portal anmelden zu müssen, stellen Sie die Verbindungsmöglichkeit der EZCast Pro Box II auf `Nur über Router` um.

![Verbindung - Nur via Router](/assets/img/ezcastpro.II.via.Router.only.settings.png)

Weitere Informationen zu den Netzwerkschnittstellen von EZCast Pro II sind im Rubrik [Verbindung](adv.settings.md#networkinterfaces) in der Funktion Erweiterte Einstellungen zu finden.

Mit der Einstellung `Nur über Router` wird der Access-Point der EZCast Pro Box II  ausgeschaltet und Sie können nur über Ihren Router mit der Box verbinden. Die SSID und das Passwort werden ausgegraut und die vom Router vergebenen IP-Adresse bzw. die statische IP-Adresse der Box wird auf der Startseite angezeigt (unten links), wie unten abgebildet:

![](/assets/img/ezcastpro.II.via.Router.only.png)

!!! info "Info"

    Mit Miracast handelt es sich trotz der o.g. Einstellung immer um eine direkte Miracast-Verbindung (P2P), die als zusätzliche WLAN-Verbindung nur zur Übertragung des Bildschirms ausgebaut wird. Für die Internetinhalte verwendet das Endgerät die bisherige bzw. die zuletzt verbundene WLAN-Verbindung und dafür müsste der Nutzer sich über die Anmeldeseite angemeldet haben. Das Protokoll Miracast kann sogar auch deaktiviert werden, wenn gewünscht.