[README.md](https://github.com/user-attachments/files/31273297/README.md)
# Vectro – Leadership-Auswahl

Dieses Paket enthält ausschließlich die drei ausgewählten Discord-Entwürfe:

1. **About Vectro – Poster:** klassisches Discohook-Embed mit bildstarker Story-Card.
2. **Staff Directory – Detailansicht:** Discord Components V2 mit einer Person pro Zeile.
3. **Staff Directory – Executive Minimal:** Discord Components V2 mit Gruppenbild und kompakter Aufgabenliste.

## Ordner

- `about-poster/` – Poster, Discohook-JSON und Vorschau
- `components-v2/` – JSON-Dateien der detaillierten Staff-Ansicht
- `staff-executive/` – Gruppenbilder, Components-V2-JSONs und Vorschau
- `assets/` – echtes Vectro-Markenzeichen, Bot-Avatar und neutrale Staff-Platzhalter
- `previews/` – Vorschau der detaillierten Staff-Ansicht

## Verwendung

### About Vectro

`about-poster/json/about-vectro.json` kann in Discohook importiert werden. Vor dem Senden müssen die Beispiel-URLs `https://DEIN-DIREKTER-LINK/...` durch direkte, öffentlich erreichbare Bild-URLs ersetzt werden.

### Staff Directory

Die Staff-Varianten verwenden Discord **Components V2**. Diese Payloads werden über einen Bot oder Webhook-Endpunkt gesendet; Discohook unterstützt nicht jede Components-V2-Struktur vollständig. Die Dateien sind bereits auf drei Nachrichten aufgeteilt: Leadership, Rocket League sowie Management & Community.

## Echte Fotos später einsetzen

In `assets/staff/` liegt für jedes Mitglied eine gesichtslose `.webp`-Platzhalterdatei. Ersetze eine Datei durch das echte quadratische Teamfoto unter demselben Namen oder ändere die jeweilige URL im JSON. Empfohlen: mindestens 800 × 800 px, quadratisch, Person mittig, dunkler Hintergrund.

Die Figuren sind absichtlich anonym und ohne Gesicht. Das Vectro-Trikot und das bereitgestellte Vectro-Logo dienen nur als Layoutvorschau.

