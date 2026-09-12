# PA Lerntrainer – GitHub Pages

Fertige mobile Web-App für GitHub Pages. Sie funktioniert auf iPhone, Android und Desktop und kann auf dem iPhone zum Home-Bildschirm hinzugefügt werden.

## In 5 Schritten online stellen

1. Auf GitHub ein neues Repository erstellen, z. B. `pa-lerntrainer`.
2. Den Inhalt dieses Ordners **direkt in das Repository** hochladen: `index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll` und den Ordner `icons`.
3. Im Repository zu **Settings → Pages** gehen.
4. Unter **Build and deployment** bei Source **Deploy from a branch** wählen, Branch **main** und Ordner **/(root)** auswählen, dann **Save**.
5. Nach kurzer Zeit erscheint oben die öffentliche GitHub-Pages-Adresse. Diese in Safari öffnen.

## Als App auf dem iPhone installieren

In Safari die GitHub-Pages-Adresse öffnen → **Teilen** → **Zum Home-Bildschirm** → **Hinzufügen**.

Danach startet der Lerntrainer nahezu wie eine normale App. Nach dem ersten erfolgreichen Laden kann er dank Service Worker auch offline verwendet werden.

## Aktualisieren

Wenn du später eine neue Version von `index.html` hochlädst und die Offline-Version auf Geräten sicher aktualisiert werden soll, ändere in `sw.js` z. B. `pa-lerntrainer-v1` auf `pa-lerntrainer-v2`.
