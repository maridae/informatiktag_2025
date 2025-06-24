# Informatiktag 2025 📱

## 🚀 Lokales Testen

### Mit Node.js/npm (Empfohlen)
```bash
npm install
npm run dev    # Startet Server und öffnet Browser
```

## ✅ Implementierte Features

- **📱 Mobile-First Design** mit Tailwind CSS
- **🔄 Offline-Funktionalität** - Service Worker mit Cache-Strategien
- **🚫 Offline-Erkennung** - Automatische Benachrichtigung bei Verbindungsproblemen
- **🔄 Auto-Updates** - Hintergrund-Synchronisation

## 🔧 Projekt-Struktur

```
informatiktag/
├── index.html         # Haupt-App
├── sw.js              # Service Worker (Offline-Cache)
├── manifest.json      # PWA-Manifest
├── js/app.js          # JavaScript-Logik
├── data/
│   ├── events.json    # Event-Daten
│   ├── stations.json  # Station-Daten
├── assets/            # Bilder & Icons
└── package.json       # NPM-Konfiguration
```
