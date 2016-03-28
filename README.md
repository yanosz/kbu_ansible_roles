Unter anderem werden die folgenden Rollen zur Einheitlichen Konfiguration der Server im KBU-Freifunk-Projekt verwenet.

#### Rolle: [kbu_backuppc](kbu_backuppc)
Einrichtung eines Server zur Anbindung an backuppc.
* Installiert rsync und sudo
* Erstellt einen Benutzer `backuppc` - Hinterlegt den SSH-Key des Server
* Gibt dem Benutzer `backuppc` volle sudo-Rechte für `/usr/bin/rsync --server --sender *`
