# Dokumentations-Index

Übersicht über alle verfügbaren Dokumentationsdateien für das "Finde den Impostor - Bibel Edition" Projekt.

## 📋 Haupt-Dokumentation

| Datei | Beschreibung | Zielgruppe |
|-------|--------------|------------|
| [`README.md`](../README.md) | Projekt-Übersicht und Schnellstart | Alle Benutzer |
| [`CHANGELOG.md`](../CHANGELOG.md) | Versionshistorie und Änderungen | Entwickler, PM |
| [`CONTRIBUTING.md`](../CONTRIBUTING.md) | Beitragsleitfaden und Standards | Entwickler |

## 🛠️ Technische Dokumentation

| Datei | Beschreibung | Zielgruppe |
|-------|--------------|------------|
| [`DEVELOPMENT.md`](DEVELOPMENT.md) | Architektur und Code-Details | Entwickler |
| [`FEATURES.md`](FEATURES.md) | Detaillierte Feature-Beschreibungen | PM, QA, Entwickler |

## 📱 Asset-Dokumentation

| Datei | Beschreibung | Zielgruppe |
|-------|--------------|------------|
| [`screenshots/SCREENSHOTS.md`](../screenshots/SCREENSHOTS.md) | Screenshot-Dokumentation | Design, Marketing |

## 📂 Ordner-Struktur

```
📁 Projekt-Root/
├── 📄 README.md                    # Haupt-Dokumentation
├── 📄 CHANGELOG.md                 # Versionshistorie  
├── 📄 CONTRIBUTING.md              # Entwickler-Leitfaden
├── 📁 docs/                        # Erweiterte Dokumentation
│   ├── 📄 INDEX.md                 # Diese Datei
│   ├── 📄 DEVELOPMENT.md           # Technische Details
│   └── 📄 FEATURES.md              # Feature-Dokumentation
├── 📁 screenshots/                 # App-Screenshots
│   └── 📄 SCREENSHOTS.md           # Screenshot-Dokumentation
└── 📁 app/                         # Android-Projekt
    └── 📁 build/outputs/apk/debug/ # APK-Download
        └── 📄 app-debug.apk        # Installierbare App
```

## 🎯 Dokumentation für verschiedene Zielgruppen

### Für Arbeitgeber/Recruiter
1. **Start:** [`README.md`](../README.md) - Projekt-Übersicht
2. **Download:** [`app-debug.apk`](../app/build/outputs/apk/debug/app-debug.apk) - App testen
3. **Details:** [`FEATURES.md`](FEATURES.md) - Was kann die App?

### Für Entwickler
1. **Start:** [`README.md`](../README.md) - Projekt-Setup
2. **Architektur:** [`DEVELOPMENT.md`](DEVELOPMENT.md) - Code-Details
3. **Beitragen:** [`CONTRIBUTING.md`](../CONTRIBUTING.md) - Standards

### Für Projektmanager
1. **Übersicht:** [`FEATURES.md`](FEATURES.md) - Alle Funktionen
2. **Historie:** [`CHANGELOG.md`](../CHANGELOG.md) - Entwicklungsfortschritt
3. **Assets:** [`screenshots/SCREENSHOTS.md`](../screenshots/SCREENSHOTS.md) - Visuelle Dokumentation

## 📖 Leseempfehlung

**Schnellstart (5 Min):** README.md → APK Download → App testen  
**Vollständig (15 Min):** README.md → FEATURES.md → DEVELOPMENT.md  
**Entwickler:** CONTRIBUTING.md → DEVELOPMENT.md → Code-Review
