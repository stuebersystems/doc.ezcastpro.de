# Linux

Mit einem EZCast Pro II Gerät stehen Ihnen zum Übertragen Ihres Bildschirms mit Hilfe des Google Chrome Browsers zwei Möglichkeiten zur Verfügung:

1. Wer lediglich seinen Bildschirm übertragen möchte, kann die Funktion [Streamen](#linuxchromecast) im Google Chrome Browser verwenden:

![Übertragungsquelle](/assets/img/Linux.Chrome_select_stream2.png)

2. Die [EZCast Pro Chrome Erweiterung](#LinuxInstallApp) bietet sowohl für den Moderator als auch für die anderen Teilnehmer einer Präsentation, verschiedene erweiterte Kontrollmöglichkeiten und Übertragungsfunktionen, die sonst bei der  Funktion `Streamen..` im Chrome Browser nicht möglich sind:

![Übertragungsquelle](/assets/img/EZCastPro.Chrome.App.png)

In dieser Anleitung wird erklärt, wie man unter Ubuntu 20.04 Google Chrome installiert. Der Chrome Browser kann jedoch auf vielen Distributions wie [Debian](https://www.debian.org/distrib/), [Kali](https://www.kali.org/), [Linux Mint](https://linuxmint.com/), [Puavo](https://puavo.org/), [Suse](https://www.suse.com/download/sled/) und [LinuxMuster](https://www.linuxmuster.net)installiert werden.


## Chromecast auf EZCast Pro freischalten

Standardmäßig ist Chromecast auf EZCast Pro II-Geräten aktiviert. Sollten Sie die Funktion jedoch erneut aktivieren wollen, finden Sie die entsprechende Option `Chromecast` unter [Erweiterte Einstellungen](adv.settings.md#Chromecast):

![](/assets/img/Chromecast-support.png)

## Google Chrome installieren

* Drücken Sie `STRG` + `Alt` + `T`, um ein Terminal-Fenster zu öffnen.

* Paketlisten aktualisieren

```
apt-get update
```

* Führen Sie anschließend folgende zwei Befehle aus:

```
$ wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
$ sudo apt install ./google-chrome-stable_current_amd64.deb
```

## 1. Aus dem Chrome-Browser Streamen {#linuxchromecast}

* Suchen Sie Google Chrome und führen Sie ihn aus:

![](/assets/img/Linux.Launch.Chrome.png)

* Wählen Sie über die drei Punkte oben rechts den Menüpunkt `Streamen...`

![Streamen..](/assets/img/Linux.Chrome_stream.png)

Wählen Sie die gewünschte Übertragungsquelle aus:

+ `Tab streamen` - Überträgt standardmäßig nur den aktiven Tab
+ `Desktop streamen` - Überträgt den gesamten Computerbildschirm 
+ `Datei streamen` - Bietet beste Leistung zum Video abspielen

![Übertragungsquelle](/assets/img/Linux.Chrome_select_stream2.png)

Um die Übertragung zu starten, wählen Sie einfach den gewünschten Empfänger aus.

![Übertragung starten](/assets/img/Linux.Chrome_start_stream.png)

Um die Übertragung zu beenden, klicken Sie nochmal auf den Empfänger.

![Übertragung beenden](/assets/img/end_stream.png)

Per Rechtsklick kann man Streamen-Symbol an die Symbolleiste anheften:

![Streamen-Symbol immer zeigen](/assets/img/Linux.Chrome.Always_show_icon.png)

## 2. Erweiterte Funktion. EZCast Pro Chrome Erweiterung 

### Erweiterung installieren {#LinuxInstallApp}

Fügen Sie die [EZCastPro Chrome Erweiterung](https://chrome.google.com/webstore/detail/ezcastpro/kngnopamkonohfcjpdjjecalmbifepfl/related) hinzu:

![EZCast Pro im App-Store](/assets/img/EZCastPro.Chrome.WebStore.Google.png)

### App mit EZCast Pro verbinden

Wenn Sie Ihr EZCast Pro Gerät richtig [eingerichtet](quickstart.md#Connect_ProBoxII) haben, erscheint folgende Startseite auf dem Bildschirm:

![Die Startseite](/assets/img/ProIIDongle_landingpage.png)

Gehen Sie jetzt wie folgt vor:

1.  Von Ihrem Linux-Gerät verbinden Sie sich mit der SSID, die oben links auf dem Bildschirm angezeigt wird, wie oben abgebildet. Das Kennwort wird standardmäßig ebenfalls angezeigt.

2.  Suchen Sie und starten die `EZCastPro` App:

    ![](/assets/img/Linux.Launch.EZCastPro.png)

3.  Klicken Sie auf die Schaltfläche `Search Devices`:

    ![Nach EZCast Pro Geräten suchen](/assets/img/chromeextension.searchdevices.png)

4.  Wählen Sie Ihr EZCast Pro Gerät aus:

	![Nach EZCast Pro Geräten suchen](/assets/img/chrome-windows_device-list.png)

5.  Um Ihren Bildschirm zu spiegeln, wählen die Schaltfläche `Spiegel Ein`:

    ![Ihr EZCast Pro Gerät auswählen](/assets/img/chromeextension.mirror.png)

