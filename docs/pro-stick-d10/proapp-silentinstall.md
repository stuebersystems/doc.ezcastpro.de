# Unbeaufsichtigte Installation der Software

Mit den unten stehenden Befehlen können Sie die EZCast Pro Software unter Windows unbeaufsichtigt (silent) installieren, reparieren und auch wieder deinstallieren.

## Vorbereitung

Laden Sie die EZCast Pro Software [für Windows herunter](https://ezcast-pro.com/download/ezcastpro-app/windows/).

## Beispiele

Es folgen Beispielaufrufe, die Sie auf Kommandozeilenebene ausführen können.

+ Unbeaufsichtigte Installation:
 
    ```
    EZCastPro_Win2.11.0.175.exe -s
    ```

+ Unbeaufsichtigte Installation ohne Neustart:

    ```
    EZCastPro_Win2.11.0.175.exe -s -var:Reboot=0
    ```

+ Unbeaufsichtigte Installation mit benutzerdefiniertem Ordner:

    ```
    EZCastPro_Win2.11.0.175.exe -s var:InstallPath="c:\My Folder"
    ```

+ Unbeaufsichtigte Installation mit benutzerdefiniertem Ordner + ohne Neustart:

    ```
    EZCastPro_Win2.11.0.175.exe -s var:InstallPath="c:\My Folder" -var:Reboot=0
    ```

+ Unbeaufsichtigte Deinstallation:

    ```
    EZCastPro_Win2.11.0.175.exe -s -u
    ```

+ Unbeaufsichtigte Deinstallation ohne Neustart:

    ```
    EZCastPro_Win2.11.0.175.exe -s -u -var:Reboot=0
    ```

+ Unbeaufsichtigte Reparatur:

    ```
    EZCastPro_Win2.11.0.175.exe -s -r
    ```