RIFFBOOK – INSTALLIERBARE WEB-APP
==================================

Enthalten:
- index.html: RiffBook Tab-Editor
- manifest.webmanifest: App-Name und Anzeige-Einstellungen
- sw.js: grundlegender Offline-Cache
- icons/riffbook.svg: App-Icon

WICHTIG:
Eine installierbare Web-App benötigt eine HTTPS-Webadresse (oder localhost).
Die Dateien allein können nicht direkt aus einem lokalen Dateipfad als PWA installiert werden.

Einfache kostenlose Veröffentlichung mit GitHub Pages:
1. Ein GitHub-Konto erstellen/anmelden.
2. Ein neues Repository erstellen, z. B. "riffbook".
3. Alle Dateien und den Ordner "icons" aus diesem Paket ins Repository hochladen.
4. In den Repository-Einstellungen unter "Pages" die Veröffentlichung aus dem main-Branch und dem Root-Verzeichnis aktivieren.
5. Nach der Veröffentlichung die angezeigte HTTPS-Adresse öffnen.

Android:
- Die HTTPS-Adresse in Chrome öffnen.
- Menü ⋮ > "App installieren" oder "Zum Startbildschirm hinzufügen".

Windows:
- Die HTTPS-Adresse in Edge oder Chrome öffnen.
- Das Installieren-Symbol in der Adressleiste oder Browser-Menü > "App installieren" auswählen.

Speicherung:
Riffs werden weiterhin im lokalen Browser gespeichert. Sie werden NICHT automatisch synchronisiert.
Nutze in RiffBook "Backup exportieren" und "Backup importieren", um sie zwischen Geräten zu übertragen.
Bewahre Backups an einem sicheren Ort auf.

Hinweis:
Die App ist eine erste Version. Der Offline-Cache wird nach dem ersten erfolgreichen Online-Aufruf eingerichtet.
