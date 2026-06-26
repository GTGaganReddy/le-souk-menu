# Le Souk – Digitale Speisekarte

Eine professionelle, mehrsprachige Online-Speisekarte für **Le Souk · Café-Bistro**
(Universitätsstraße 25, 9020 Klagenfurt).

- **Sprachen:** Deutsch · English · Italiano · Slovenščina (Umschalter oben)
- **Design:** Gold auf Schwarz, passend zur Visitenkarte; Script-Schrift „Le Souk“
- **Hell-/Dunkelmodus:** Umschalter (Sonne/Mond) oben rechts; die Wahl wird am Gerät gespeichert. Standard ist der Dunkelmodus.
- **Optimiert für Handy** (der QR-Code führt direkt hierher)

## Auf GitHub Pages veröffentlichen (für den QR-Code)

1. Neues GitHub-Repository erstellen, z. B. `le-souk-menu`.
2. Alle Dateien hochladen: `index.html` und den Ordner `images/`.
3. Im Repo: **Settings → Pages → Branch: `main` / `(root)` → Save**.
4. Nach ~1 Minute ist die Karte erreichbar unter:
   `https://<dein-benutzername>.github.io/le-souk-menu/`
5. **Diese URL** im QR-Code hinterlegen (VistaPrint-Karte / Aufsteller).

> Tipp: Den QR-Code immer auf die GitHub-Pages-URL zeigen lassen – nicht auf eine
> einzelne Bilddatei. So kannst du die Karte jederzeit ändern, der QR bleibt gleich.

## Preise / Inhalte ändern

Alles steht in `index.html` im Abschnitt `MENU DATA` (ganz unten im `<script>`):
- Preis ändern: `p:"13,90"` anpassen.
- Gericht umbenennen: im `name`-Feld ändern.
- Ein Name als `"Text"` gilt für alle Sprachen; als `{de:…,en:…,it:…,sl:…}` wird übersetzt.

### ⚠️ Bitte prüfen
Die **Tajine-Beschreibungen** habe ich passend zur jeweiligen Spezialität formuliert
(z. B. Marrakesch = Lamm/Aprikosen, Hafen = Fisch/Meeresfrüchte, Fès = Hähnchen/Zitrone).
Bitte einmal gegen die echten Rezepte gegenlesen und ggf. anpassen.
Die **Preise** stammen aus den Fotos der Kassa (POS) – bei Bedarf korrigieren.

## „Meine Auswahl" (Das will ich essen)
Gäste können mit dem **+** bei jedem Gericht/Getränk eine persönliche Liste anlegen.
Unten rechts erscheint **Meine Auswahl** mit Zähler; ein Tipp zeigt die Liste mit
**Moes Foto** – einfach Moe zeigen. Alles bleibt am Gerät (kein Versand, keine Anmeldung).

**Moes Foto austauschen:** Datei `images/moe.jpg` durch ein neues, möglichst
quadratisches Foto ersetzen (gleicher Name). Es wird automatisch rund dargestellt.

## Bilder
Im Ordner `images/`: `logo.jpg`, `hero-tajine.jpg`, `hero-couscous.jpg`,
`tajine-prunes.jpg`, `sign.jpg`. Zum Austauschen einfach gleichnamig ersetzen.
