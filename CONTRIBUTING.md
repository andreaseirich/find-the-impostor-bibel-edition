# Beitrag zum Projekt

Vielen Dank für Ihr Interesse an der "Finde den Impostor - Bibel Edition" App! Diese Dokumentation beschreibt, wie Sie zu diesem Projekt beitragen können.

## 📋 **Übersicht**

Dieses Projekt wurde als Portfolio-Demonstration für professionelle Android-Entwicklungskompetenzen erstellt. Es zeigt moderne Entwicklungspraktiken, saubere Architektur und benutzerorientiertes Design.

## 🎯 **Projektphilosophie**

- **Christliche Werte:** Alle Inhalte und Features respektieren christliche Überzeugungen
- **Technische Exzellenz:** Hohe Code-Qualität und moderne Android-Standards
- **Benutzerfreundlichkeit:** Intuitive, barrierefreie Gestaltung
- **Bildungswert:** Förderung biblischen Wissens durch spielerische Vermittlung

## 🛠️ **Entwicklungsumgebung**

### Voraussetzungen
- **Android Studio** (neueste stabile Version)
- **JDK 17** oder höher
- **Android SDK** mit API Level 24-34
- **Kotlin Plugin** für Android Studio
- **Git** für Versionskontrolle

### Projekt-Setup
```bash
# Repository klonen
git clone [repository-url]
cd find-the-impostor-bible-edition

# Android Studio öffnen und Projekt importieren
# Gradle Sync durchführen
# Emulator oder physisches Gerät verbinden
```

## 📁 **Projektstruktur**

```
app/src/main/java/com/bibeledition/impostor/
├── MainActivity.kt          # Hauptmenü und Spielkonfiguration
├── GameActivity.kt         # Spiellogik und Gesture-Handling
├── GameLogic.kt           # Kernspielregeln und Zustandsverwaltung
├── BiblicalWords.kt       # Wortdatenbank und Tipp-System
└── PlayerAdapter.kt       # RecyclerView Adapter für Spielerliste

app/src/main/res/
├── layout/                # XML Layout-Dateien
├── values/               # Strings, Colors, Themes
├── drawable/            # Icons und Grafiken
└── mipmap-*/           # App-Icons verschiedener Auflösungen
```

## 🎨 **Design-Richtlinien**

### Farbschema
```kotlin
// Primäre Farben (biblisch inspiriert)
bible_blue: #1976D2        // Königsblau - Göttlichkeit, Himmel
bible_gold: #FFD700        // Gold - Herrlichkeit, Heiligkeit
background_light: #FAFAFA  // Reines Weiß - Reinheit, Licht

// Funktionale Farben
impostor_red: #D32F2F      // Rot - Warnung, Impostor-Rolle
innocent_green: #388E3C    // Grün - Hoffnung, Innocent-Rolle
text_primary: #212121      // Dunkles Grau - Haupttext
```

### UI/UX Prinzipien
- **Material Design 3** Standards befolgen
- **Card-basierte Layouts** für klare Informationsgruppierung
- **Große Touch-Bereiche** (min. 48dp) für Barrierefreiheit
- **Konsistente Abstände** (8dp Grid-System)
- **Lesbare Typografie** (min. 16sp für Body-Text)

## 🔧 **Code-Standards**

### Kotlin Coding Conventions
```kotlin
// Klassen-Namen: PascalCase
class GameActivity : AppCompatActivity()

// Funktionen und Variablen: camelCase
private fun updateCurrentPlayer()
private lateinit var playerAdapter: PlayerAdapter

// Konstanten: SCREAMING_SNAKE_CASE
companion object {
    private const val MIN_PLAYERS = 3
    private const val MAX_PLAYERS = 10
}

// Null Safety verwenden
private var currentPlayer: Player? = null
private lateinit var gameSettings: GameSettings
```

### Architektur-Richtlinien
- **Single Responsibility Principle** - Eine Klasse, eine Aufgabe
- **Dependency Injection** wo sinnvoll
- **ViewBinding** statt findViewById verwenden
- **Resource Externalisierung** (strings.xml, colors.xml)
- **Error Handling** mit Try-Catch und Null-Checks

## 📚 **Biblische Inhalte**

### Wort-Kategorien
1. **Personen** - Biblische Figuren (Abraham, David, Paulus...)
2. **Orte** - Heilige Stätten (Jerusalem, Bethlehem, Galiläa...)
3. **Objekte** - Religiöse Gegenstände (Arche, Kreuz, Tempel...)
4. **Konzepte** - Christliche Begriffe (Gnade, Hoffnung, Erlösung...)
5. **Bücher** - Bibelbücher (Genesis, Psalmen, Johannes...)

### Tipp-System Richtlinien
- Tipp-Wörter sollen **thematisch verwandt** sein
- **Nicht zu offensichtlich** - Herausforderung erhalten
- **Biblischer Kontext** muss gewahrt bleiben
- **Mehrere Optionen** pro Grundwort für Abwechslung

## 🧪 **Testing-Richtlinien**

### Unit Tests
- **Geschäftslogik** in GameLogic.kt testen
- **Wort-Zuordnungen** in BiblicalWords.kt validieren
- **Edge Cases** für Spielerzahl und Impostor-Anzahl

### UI Tests
- **Benutzerinteraktionen** (Swipe-Gesten, Button-Klicks)
- **Navigationspfade** zwischen Activities
- **Eingabe-Validierung** für Spielernamen

### Integration Tests
- **Vollständige Spielabläufe** von Setup bis Diskussion
- **Verschiedene Gerätegrößen** und Orientierungen
- **Performance** unter verschiedenen Bedingungen

## 🌐 **Lokalisierung**

### Aktuelle Sprachen
- **Deutsch** (vollständig implementiert)

### Geplante Erweiterungen
- **Englisch** - Internationale Reichweite
- **Weitere Sprachen** je nach Community-Bedarf

### Lokalisierungs-Richtlinien
- Alle Texte in `strings.xml` externalisieren
- Kulturelle Sensibilität bei Übersetzungen
- Biblische Begriffe authentisch übersetzen
- UI-Layout für längere Texte anpassen

## 🚀 **Contribution Workflow**

### 1. Issue erstellen
- **Bug Reports** mit detaillierter Beschreibung
- **Feature Requests** mit Begründung und Use Cases
- **Verbesserungsvorschläge** für UX/UI

### 2. Development
- Feature Branch erstellen (`feature/neue-funktion`)
- Code-Standards befolgen
- Tests hinzufügen/aktualisieren
- Dokumentation aktualisieren

### 3. Pull Request
- **Aussagekräftige Beschreibung** der Änderungen
- **Screenshots** für UI-Änderungen
- **Testing-Notizen** für Reviewer
- **Breaking Changes** dokumentieren

## 🎓 **Lernressourcen**

### Android Development
- [Android Developer Documentation](https://developer.android.com/)
- [Kotlin Official Documentation](https://kotlinlang.org/docs/)
- [Material Design Guidelines](https://material.io/design)

### Biblische Ressourcen
- [BibleGateway](https://www.biblegateway.com/) - Bibelverse und Konkordanz
- [Bible Study Tools](https://www.biblestudytools.com/) - Wörterbücher und Kommentare

## 📞 **Kontakt & Community**

Dieses Projekt dient als Portfolio-Demonstration und zeigt professionelle Entwicklungskompetenzen in:

- **Native Android Development**
- **Kotlin Programming**
- **Material Design Implementation**
- **Clean Architecture**
- **User Experience Design**

---

**Entwickelt mit ❤️ für die christliche Gemeinschaft**

*"Alles, was ihr tut, das tut von Herzen als dem Herrn und nicht den Menschen." - Kolosser 3,23*
