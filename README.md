Unter anderem werden die folgenden Rollen zur einheitlichen Konfiguration der Server im KBU-Freifunk-Projekt verwendet.

Die Zuordnung zwischen Rollen und Servern wird yanosz/kbu_ansible umgesetzt.

#### Rolle: [kbu_backuppc](kbu_backuppc)
Einrichtung eines Server zur Anbindung an backuppc.
* Installiert rsync und sudo
* Erstellt einen Benutzer `backuppc` - Hinterlegt den SSH-Key des Server
* Gibt dem Benutzer `backuppc` volle sudo-Rechte für `/usr/bin/rsync --server --sender *`
