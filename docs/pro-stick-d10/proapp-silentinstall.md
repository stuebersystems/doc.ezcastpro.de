# Unbeaufsichtigte Installation der Software

Mit den unten stehenden Befehlen können Sie die EZCast Pro Software unter Windows unbeaufsichtigt (silent) installieren, reparieren und auch wieder deinstallieren.

!!! info "Hinweis"

    Bei Bedarf können Sie von uns ein Installationspaket im **MSI-Format** erhalten. [Schreiben](https://www.stueber.de/contact.php?from=ezcastpro) Sie uns einfach an.
	
## Vorbereitung

Laden Sie die EZCast Pro Software [für Windows herunter](https://www.ezcast.com/app/ezcast/pro/windows) 

## Beispiele

+ Unbeaufsichtigte Installation:
  ``` batch
  EZCastPro_Win2.11.0.175.exe -s
  ```

+ Unbeaufsichtigte Installation ohne Neustart:
  ``` batch
  EZCastPro_Win2.11.0.175.exe -s -var:Reboot=0
  ```

+ Unbeaufsichtigte Installation mit benutzerdefiniertem Ordner:
  ``` batch
  EZCastPro_Win2.11.0.175.exe -s var:InstallPath="c:\My Folder"
  ```

+ Unbeaufsichtigte Installation mit benutzerdefiniertem Ordner + ohne Neustart:
  ``` batch
  EZCastPro_Win2.11.0.175.exe -s var:InstallPath="c:\My Folder" -var:Reboot=0
  ```

+ Unbeaufsichtigte Deinstallation:
  ```` batch
  EZCastPro_Win2.11.0.175.exe -s -u
  ````

+ Unbeaufsichtigte Deinstallation ohne Neustart:
  ``` batch
  EZCastPro_Win2.11.0.175.exe -s -u -var:Reboot=0
  ```

+ Unbeaufsichtigte Reperatur:
  ``` batch
  EZCastPro_Win2.11.0.175.exe -s -r
  ```
