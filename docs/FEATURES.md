# Feature-Dokumentation

Detaillierte Beschreibung aller Features der "Finde den Impostor - Bibel Edition" App.

## Kernfunktionen

### 🎮 Spielmechanik

#### Lokales Multiplayer-Spiel
- **3-10 Spieler** auf einem einzigen Android-Gerät
- **Sequenzielle Geräteübergabe** zwischen den Spielern
- **Automatische Validierung** der Spielerzahl und Impostor-Anzahl

#### Intuitive Wischgesten-Steuerung
- **Upward-Swipe** zur Rollenaufdeckung
- **Custom GestureDetector** Implementation
- **Smooth Animation** bei Rollenübergängen

#### Flexible Impostor-Konfiguration
- **Variable Anzahl** von 1 bis (Spielerzahl-1) Impostors
- **Automatische Begrenzung** verhindert ungültige Konfigurationen
- **Real-time Validierung** während der Eingabe

### 📚 Biblischer Inhalt

#### Umfangreiche Wortdatenbank
- **500+ biblische Begriffe** aus verschiedenen Kategorien
- **Kategorisierte Auswahl:**
  - Biblische Personen (Abraham, David, Paulus...)
  - Heilige Orte (Jerusalem, Bethlehem, Galiläa...)
  - Religiöse Objekte (Arche, Kreuz, Tempel...)
  - Christliche Konzepte (Gnade, Hoffnung, Erlösung...)
  - Bücher der Bibel (Genesis bis Offenbarung)

#### Intelligentes Tipp-System
- **Thematisch verwandte Begriffe** als Impostor-Tipps
- **Über 200 Tipp-Zuordnungen** manuell kuratiert
- **Fallback-System** für nicht-zugeordnete Begriffe
- **Schwierigkeitsbalancierung** durch sinnvolle Tipps

### 🎨 Benutzeroberfläche

#### Material Design 3 Implementation
- **Moderne Card-Layouts** für strukturierte Informationsdarstellung
- **Consistent Spacing** mit 8dp Grid-System
- **Responsive Design** für verschiedene Bildschirmgrößen
- **Touch-optimierte Elemente** (min. 48dp Touch-Bereiche)

#### Biblisch inspirierte Farbpalette
- **Königsblau (#1976D2)** - Primärfarbe für Göttlichkeit/Himmel
- **Gold (#FFD700)** - Sekundärfarbe für Herrlichkeit/Heiligkeit
- **Reines Weiß (#FAFAFA)** - Hintergrund für Reinheit/Licht
- **Impostor Rot (#D32F2F)** - Warnfarbe für Impostor-Rolle
- **Innocent Grün (#388E3C)** - Hoffnungsfarbe für Innocent-Rolle

## Erweiterte Features

### Barrierefreie Gestaltung
- **Hohe Kontraste** für bessere Lesbarkeit
- **Große Schriftgrößen** (min. 16sp für Body-Text)
- **Screen Reader Support** durch semantische UI-Elemente
- **Einhand-Bedienung** optimiert (Portrait-Orientierung)

### Performance-Optimierungen
- **Lazy Loading** der Wortdatenbank für schnelle Startzeiten
- **Memory-effiziente** RecyclerView Implementation
- **Hardware-beschleunigte** Animationen
- **Optimierte APK-Größe** (< 5 MB)

### Offline-Funktionalität
- **100% offline spielbar** - keine Internetverbindung erforderlich
- **Lokale Datenspeicherung** aller biblischen Begriffe
- **Keine externe API-Abhängigkeiten**
- **Batteriefreundlich** durch minimale Hintergrundaktivität

## Spielablauf-Features

### 1. Spielvorbereitung
- **Dynamische Spielerliste** mit Add/Remove-Funktionalität
- **Duplikatsprüfung** verhindert identische Spielernamen
- **Real-time UI-Updates** bei Spieler-Änderungen
- **Impostor-Anzahl-Slider** mit automatischer Begrenzung

### 2. Rollenzuteilung
- **Zufällige Rollenverteilung** mit garantierter Impostor-Anzahl
- **Farbkodierte Rollenanzeige** für sofortige Erkennung
- **Wort/Tipp-Zuordnung** basierend auf Rolle und Einstellungen
- **Sichere Rollenaufdeckung** durch Gesture-basierte Interaktion

### 3. Diskussionsphase
- **Nahtloser Übergang** nach allen Rollenaufdeckungen
- **Neustart-Option** für weitere Spielrunden
- **Hauptmenü-Rückkehr** für Konfigurationsänderungen
- **State Management** für konsistente UI-Zustände

## Technische Features

### Architektur
- **MVVM Pattern** für saubere Code-Trennung
- **Single Activity** mit Fragment-ähnlicher Navigation
- **State-basierte UI** für konsistente Benutzererfahrung
- **Typsichere Data Classes** für Konfigurationsdaten

### Datenmanagement
- **Immutable Data Structures** für Thread-Sicherheit
- **Kotlin Collections** für effiziente Datenoperationen
- **Null Safety** durch Kotlin Type System
- **Resource Management** mit automatischer Speicherfreigabe
