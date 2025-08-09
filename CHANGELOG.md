# Changelog

Alle wichtigen Änderungen an diesem Projekt werden in dieser Datei dokumentiert.

Das Format basiert auf [Keep a Changelog](https://keepachangelog.com/de/1.0.0/),
und dieses Projekt folgt [Semantic Versioning](https://semver.org/lang/de/).

## [1.0.0] - 2024-01-15

### Hinzugefügt
- **Vollständige Erstveröffentlichung** der "Finde den Impostor - Bibel Edition" Android-App
- **Kernspiellogik** mit Impostor-Identifikationsmechanik
- **Umfangreiche biblische Wortdatenbank** mit 500+ Begriffen aus verschiedenen Kategorien:
  - Biblische Personen (Abraham, David, Paulus, Maria, etc.)
  - Heilige Orte (Jerusalem, Bethlehem, Galiläa, etc.)
  - Religiöse Objekte (Arche, Kreuz, Tempel, etc.)
  - Christliche Konzepte (Gnade, Hoffnung, Erlösung, etc.)
  - Bücher der Bibel (Genesis bis Offenbarung)
- **Intelligentes Tipp-System** mit thematisch verwandten Begriffen für Impostors
- **Intuitive Swipe-Gesten-Steuerung** für Rollenaufdeckung
- **Material Design 3 UI** mit biblisch inspirierter Farbpalette
- **Flexible Spielkonfiguration**:
  - 3-10 Spieler Unterstützung
  - Variable Impostor-Anzahl (1 bis n-1)
  - Optional aktivierbare Impostor-Tipps
- **Vollständige deutsche Lokalisierung**
- **Offline-Funktionalität** ohne Internetanforderungen
- **Responsive Card-Layout** für optimale Benutzerfreundlichkeit
- **Barrierefreie Gestaltung** mit hohen Kontrasten

### Technische Implementierung
- **Native Android-Entwicklung** in Kotlin
- **MVVM-Architektur** für saubere Code-Trennung
- **ViewBinding** für effiziente UI-Referenzen
- **RecyclerView** für dynamische Spielerlisten-Verwaltung
- **Custom GestureDetector** für Swipe-Interaktionen
- **State-basiertes UI-Management**
- **Resource-optimierte Speichernutzung**

### Sicherheit & Performance
- **Null Safety** durch Kotlin's Type System
- **Memory-effiziente** Implementierung
- **Smooth Animationen** durch Hardware-Beschleunigung
- **Robuste Eingabe-Validierung**
- **Consistent Error Handling**

---

## Geplante Versionen

### [1.1.0] - Geplant
- **Mehrsprachige Unterstützung** (Englisch, weitere Sprachen)
- **Spielstatistiken** und Verlaufsanzeige
- **Custom Wortlisten** für Benutzer-definierte Begriffe
- **Erweiterte Accessibility-Features**

### [1.2.0] - Geplant
- **Thematische Erweiterungen** (Weihnachten, Ostern, Kirchenjahr)
- **Achievement-System** für Gamification
- **Export/Import** von Spielkonfigurationen
- **Erweiterte Statistiken** und Analysen

### [2.0.0] - Langfristig geplant
- **Online-Multiplayer** Funktionalität
- **Community-Features** zum Teilen von Wortlisten
- **Cross-Platform** Unterstützung
- **Progressive Web App** Version

---

## Entwicklungsnotizen

- **Minimum SDK:** API 24 (Android 7.0) für 94% Marktabdeckung
- **Target SDK:** API 34 (Android 14) für neueste Features
- **Dateigröße:** < 5 MB für schnelle Installation
- **RAM-Verbrauch:** < 50 MB für ressourcenschonende Ausführung
- **Startup-Zeit:** < 2 Sekunden für optimale Benutzererfahrung
