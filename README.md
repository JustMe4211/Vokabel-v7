# VokabelTrainer für GitHub Pages

## Veröffentlichung

1. Auf GitHub ein neues Repository erstellen, z. B. `vokabeltrainer`.
2. Diese drei Dateien (`index.html`, `manifest.webmanifest`, `sw.js`) in das Repository hochladen.
3. In GitHub: **Settings → Pages**.
4. Bei **Build and deployment**: **Deploy from a branch** auswählen.
5. Branch `main` und Ordner `/ (root)` auswählen und speichern.
6. Nach dem Deployment zeigt GitHub die Website-Adresse an, z. B.:
   `https://DEIN-NAME.github.io/vokabeltrainer/`

## Auf dem iPad

Die Adresse in Safari öffnen → **Teilen** → **Zum Home-Bildschirm** → **Hinzufügen**.

## Wichtig

Die OCR verwendet Tesseract.js über ein CDN. Deshalb braucht die App beim ersten Auslesen eine Internetverbindung.

Das Buchformat ist auf **Englisch links / Deutsch rechts** ausgelegt. Die erkannte Tabelle wird für die Abfrage automatisch zu **Deutsch → Englisch** umgedreht.
