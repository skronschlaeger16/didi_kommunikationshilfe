# Мост – Meine Wörter · Unterstützte Kommunikation

Kostenlose, responsive Kommunikationshilfe für Wohngruppen mit Bulgarisch und Deutsch.

## Veröffentlichung auf GitHub Pages

1. Auf github.com anmelden und ein **neues öffentliches Repository** erstellen, z. B. `most-kommunikation`.
2. Alle Dateien aus diesem ZIP **direkt in das Hauptverzeichnis** des Repositorys hochladen: `index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png` (plus diese README). Nicht nur das ZIP hochladen!
3. Im Repository **Settings → Pages → Build and deployment** öffnen. Unter **Source** `Deploy from a branch` auswählen, dann `main` und `/ (root)` speichern.
4. Nach Veröffentlichung die Adresse `https://DEIN-BENUTZERNAME.github.io/most-kommunikation/` im Tablet-Browser öffnen.
5. iPad: Safari → Teilen → Zum Home-Bildschirm. Android: Chrome → Menü → App installieren / Zum Startbildschirm. App bei vorhandener Internetverbindung zunächst einmal vollständig laden, danach Flugmodus testen.

## Bedienung

- Die wichtigen Buttons Ja, Nein, Stopp, Hilfe sind immer oben.
- Die globale Suche durchsucht deutsche und bulgarische Wörter über alle Tabs.
- Karten antippen, um die Sprachausgabe zu starten.
- **⚙️ Bearbeiten** → Karten: Karten ergänzen, Übersetzungen korrigieren, eigene Bilder auswählen oder bestehende Bilder ersetzen.
- **⚙️ Bearbeiten** → Kategorien: zusätzliche Tabs anlegen.
- **⚙️ Bearbeiten** → Sicherung: lokale Anpassungen als JSON sichern und importieren.
- Eigene Bilder vom Tablet können auch ohne Internet hinzugefügt werden. Die App lädt keine Bilder aus einer Online-Piktogrammbibliothek.

## Offline und Datenschutz

Die App enthält keine externen Bildbibliotheken oder Server-APIs. Standardkarten sind in HTML eingebettet. Kartenergänzungen und eigene Fotos liegen **nur im lokalen Browser-Speicher (IndexedDB)**. Sie sind nicht automatisch auf andere Geräte synchronisiert und gehören **nicht** zu den GitHub-Dateien. Bitte regelmäßig Backups erstellen. Auf einem neuen Tablet muss die Backup-Datei importiert werden. Browserdaten löschen kann die Inhalte unwiederbringlich entfernen.

Die PWA lädt ihre Dateien bei der ersten HTTPS-Nutzung in einen Offline-Cache. Die App braucht bei gewöhnlicher Nutzung dann kein Internet; die Web-Speech-Sprachausgabe ist aber vom Browser/Betriebssystem und installierten deutschen/bulgarischen Stimmen abhängig. Vor Verwendung offline mit Flugmodus testen.

## Hinweise für UK

Die Emoji-Karten sind **keine standardisierten UK-Piktogramme**. Bitte Verständlichkeit und persönliche bulgarische Formulierungen gemeinsam mit Klient und Mutter testen und ggf. durch Fotos ersetzen. Besonders bei Schmerz, Notfall und Grenzen dürfen Bilder nicht allein ohne zusätzliche Abklärung interpretiert werden.

## Updates

Bei Änderungen an `index.html` Dateien nach GitHub hochladen; Browser lädt beim nächsten Online-Besuch die aktuelle Seite. Die lokalen Karten bleiben grundsätzlich im selben Browser-/App-Speicher, trotzdem vor jedem Update ein Backup exportieren.
