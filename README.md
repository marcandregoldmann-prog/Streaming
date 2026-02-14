# 🎬 Meine Seiten - PWA

Eine Progressive Web App mit deiner persönlichen Sammlung von Streaming-Seiten.

## 📱 Installation

### Auf dem Smartphone (Chrome/Edge):

1. Öffne die `index.html` in deinem Browser
2. Tippe auf die drei Punkte (⋮) im Browser-Menü
3. Wähle "Zum Startbildschirm hinzufügen" oder "App installieren"
4. Bestätige die Installation

### Auf dem Desktop (Chrome/Edge):

1. Öffne die `index.html` in deinem Browser
2. Klicke auf das ➕ Symbol in der Adressleiste
3. Oder: Klicke auf die drei Punkte → "App installieren"

## 🚀 Nutzung

1. **Lokale Nutzung**: Öffne einfach die `index.html` Datei
2. **Webserver**: Hoste die Dateien auf einem Webserver für volle PWA-Funktionalität

### Einfacher lokaler Webserver (optional):

```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve
```

Dann öffne: `http://localhost:8000`

## ✨ Features

- 📱 Installierbar als App auf dem Startbildschirm
- 🎨 Modernes, farbenfrohes Design
- 📂 Kategorisiert nach Serien und Filmen
- 🔗 Links öffnen sich im Standardbrowser
- 📴 Funktioniert auch offline (gespeicherte Version)

## 📁 Dateien

- `index.html` - Hauptseite
- `manifest.json` - PWA Manifest
- `service-worker.js` - Offline-Funktionalität

## 🔧 Anpassungen

Um weitere Links hinzuzufügen, bearbeite die `index.html`:

```html
<a href="DEINE-URL" class="link-button series-button" target="_blank" rel="noopener noreferrer">
    Dein Link-Name
</a>
```

Verwende:
- `series-button` für pink-rote Buttons
- `movies-button` für blaue Buttons
- `link-button` für lila Buttons (Standard)

Viel Spaß! 🎉
