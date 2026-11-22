# Lukas / 26

Geburtstagsseite für Lukas – statisches HTML, kein Build-Schritt.

- Bis **Montag, 23. November 2026, 0:00 Uhr** (deutsche Zeit) zeigt die Seite einen Countdown,
  danach automatisch die Geburtstagsseite mit Feuerwerk und Konfetti.
- Vorschau vorab: `#vorschau` an die URL hängen.
- Zeitpunkt ändern: `TARGET` im Skript am Ende von `index.html`.

## Aufbau

```
index.html          Seite, Styles und Skript
img/                Fotos
vendor/confetti.js  canvas-confetti 1.9.3 (ISC)
vendor/fireworks.js fireworks-js 2.10.8 (MIT)
```

## Lokal ansehen

```
npx serve .
```

## Deployen

Funktioniert auf jedem statischen Hosting (Vercel, Netlify, GitHub Pages) ohne Einstellungen:
Repo importieren, Framework „Other“, kein Build-Befehl, Root = Projektordner.
