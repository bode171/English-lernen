# English lernen

Englisch-Lern-App für die 5. Klasse Realschule Bayern (angelehnt an Go Ahead 5).
20 Etappen, 82 Lektionen, 310 Wörter – jedes Wort mit Bild, Schreibweise, Aussprache-Hilfe und Vorlesen (britische Frauenstimme).
Täglich 10–15 Minuten, mit automatischer Wiederholung nach dem Karteikasten-Prinzip.

## Auf GitHub Pages veröffentlichen

1. Neues Repository anlegen (z. B. `english-lernen`).
2. `index.html` und diese `README.md` hochladen („Add file → Upload files“).
3. **Settings → Pages → Branch: `main` / Ordner: `/ (root)` → Save**.
4. Nach 1–2 Minuten ist die App erreichbar unter `https://<dein-name>.github.io/english-lernen/`.
5. Am iPad in Safari öffnen → Teilen → **Zum Home-Bildschirm**. Dann startet sie wie eine App.

## Hinweise

- Der Fortschritt wird im Browser des Geräts gespeichert (localStorage). Immer auf demselben Gerät und im selben Browser lernen. Safari-Verlauf löschen setzt den Fortschritt zurück.
- Eltern-Bereich: PIN steht in `index.html` (`PARENT_PIN`). In einem öffentlichen Repository kann jeder den Code lesen.
- Für eine deutliche Stimme am iPad: Einstellungen → Bedienungshilfen → Gesprochene Inhalte → Stimmen → Englisch (Großbritannien) → z. B. „Serena“ (Premium/Erweitert) laden, dann im Eltern-Bereich auswählen.
- Wörter, Grammatik-Tipps und Sätze stehen oben im Script im Array `UNITS`, die Aussprache-Hilfen in `PRON`.
