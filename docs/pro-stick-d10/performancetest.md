# Leistungstest durchführen

Zu Support-Zwecken bitten wir Sie möglicherweise, dass Sie einen Leistungstest Ihres Gerätes durchführen. Unter normalen Bedienungen beim Testen sollte der QuattroPod die Bildschirmübertragung eines Videos ohne Probleme leisten können. Zu diesem Test benötigen Sie folgende Geräte:

* Einen Windows-PC 

* Einen QuattroPod-Empfänger

* Einen QuattroPod-Sender

## Debug Over IP durchführen {#debug.over.ip}

Laden Sie die Software [![Auto Mouse Mover](/assets/img/automousemover.icon.png)](https://www.murgee.com/auto-mouse-mover/) [Auto Mouse Mover](https://www.murgee.com/auto-mouse-mover/), die Variante `Stand Alone Application`, herunter und extrahieren Sie die .zip-Datei auf Ihrem Windows-PC:

![](/assets/img/automousemover.extract.png)

* Führen Sie die Datei **AutoMouseMover.exe** aus:

![](/assets/img/AutoMouseMover.exe.png)

* Auf der Lizenzvereinbarung wählen Sie `Agree`:

![](/assets/img/automousemover.agreement.png)

* Sie können die vorgegebenen Einstellungen übernehmen und einfach auf `Save & Hide to System Tray` klicken, um die Software in die Systemleiste zu minimieren:

![](/assets/img/automousemove.settings.png)

* Am Ende der Installation setzen Sie ein Häkchen neben `Launch Tera Term` ein und klicken Sie auf `Finish`:

![](/assets/img/automousemover.extract.png)

* Notieren Sie sich die IP-Adresse, die unten links auf der Startseite angezeigt wird.

![](/assets/img/ProIIDongle_IP.png)

* Im Dialogfenster `Neue Verbindung` geben Sie die IP-Adresse Ihres EZCast Pro Gerätes sowie den TCP-Port `8700` ein und wählen Sie den Dienst `Telnet` aus. Ihr Rechner muss sich im gleichen Netzwerk wie das EZCast Pro Gerät befinden:

![](/assets/img/teraterm.new.connection.png)

* Wurde die Verbindung erfolgreich aufgebaut, werden die Prozessinformationen im Tera-Term-Fenster angezeigt:

![](/assets/img/teraterm.data.png)

* Unter `Datei` -> `Log...` speichern Sie die Logdatei im Ordner `Dokumente` ab:

![](/assets/img/Logfile.save.png)

![](/assets/img/Logfile.save.documents.png)

!!! tip "Hinweis"
    
	Zu diesem Zeitpunkt werden alle Aktivitäten des EZCast Pro-Geräts in die Protokolldatei eingelesen. An dieser Stelle müssen Sie die Ereignisse reproduzieren, die das Problem verursacht haben z.B. die Berührungsgesten auf dem Bildschirm, sollten Sie diese jetzt ausführen, bis das Problem wieder auftritt und in der Protokolldatei aufgezeichnet wird.


* Lassen Sie uns bitte die Logdatei über unser [Ticketsystem](https://support.stueber.de) zukommen. 

![](/assets/img/logfile.ticket.png)

### Debug Over IP deaktivieren

* Schließlich am Ende des Verfahrens können Sie die Funktion **Debug Over IP** wieder deaktivieren:

![](/assets/img/proII.select.debugviaip.off.png)

* Um den `Engineer Mode` wieder auszublenden, klicken Sie auf die Funktion `Debug Mode`. Sie kehren zurück auf das Hauptmenü:

![](/assets/img/proII.select.engineermode.off.png)