# EZCast Pro Software - Silent Install

Der Begriff **Silent Install** kommt aus dem Englischen und beschreibt eine unbeaufsichtigte Installation. 

Mit den unten stehenden Befehlen können Sie die EZCast Pro Software unter Windows unbeaufsichtigt installieren:


!!! info "Hinweis"

    Bei Bedarf können unsere Kunden ein Installationspaket im **MSI-Format** bei Bedarf über uns erwerden. [Schreiben](https://www.stueber.de/contact.php?from=ezcastpro) Sie uns einfach an.
	
## Software unter Windosws herunterladen

Laden Sie bitte die Software für [Windows](https://www.ezcast.com/app/ezcast/pro/windows) herunter. 

## .EXE Bespiele

### Silent Install:

```` xml
EZCastPro_Win2.11.0.175.exe -s
````

### Silent Install ohne Neustart:

```` xml
EZCastPro_Win2.11.0.175.exe -s -var:Reboot=0
````


### Silent Install mit benutzerdefiniertem Ordner:

```` xml
EZCastPro_Win2.11.0.175.exe -s var:InstallPath="c:\My Folder"
````


### Silent Install mit benutzerdefiniertem Ordner + ohne Neustart:

```` xml
EZCastPro_Win2.11.0.175.exe -s var:InstallPath="c:\My Folder" -var:Reboot=0
````


### Silent Uninstall:

```` xml
EZCastPro_Win2.11.0.175.exe -s -u
````


### Silent Uninstall + ohne Neustart:

```` xml
EZCastPro_Win2.11.0.175.exe -s -u -var:Reboot=0
````
