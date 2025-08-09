# Entwicklungs-Dokumentation

Diese Datei enthält technische Details zur Entwicklung der "Finde den Impostor - Bibel Edition" App.

## Projektstruktur

```
app/src/main/java/com/bibeledition/impostor/
├── MainActivity.kt          # Spielkonfiguration & Spieler-Management
├── GameActivity.kt         # Hauptspiellogik & Gesture-Handling  
├── GameLogic.kt           # Spielregeln & Zustandsverwaltung
├── BiblicalWords.kt       # Wortdatenbank & Tipp-System
└── PlayerAdapter.kt       # RecyclerView für Spielerliste
```

## Architektur-Entscheidungen

### MVVM Pattern
- **Model:** GameLogic, BiblicalWords (Geschäftslogik)
- **View:** XML Layouts, Activities (UI-Darstellung)  
- **ViewModel:** Implizit in Activities (UI-Logik)

### Datenmanagement
- **Statische Wortliste** in BiblicalWords.kt (500+ Begriffe)
- **In-Memory Spielzustand** ohne Persistierung
- **Typsichere Data Classes** für Spielkonfiguration

### UI/UX Implementierung
- **Material Design 3** Komponenten
- **ViewBinding** für effiziente View-Referenzen
- **Custom GestureDetector** für Swipe-Interaktionen
- **Farbkodierte Rollen** (Grün/Rot) für intuitive UX

## Performance-Optimierungen

- **Lazy Loading** der Wortdatenbank
- **Efficient RecyclerView** mit ViewHolder Pattern
- **Memory-optimierte** Datenstrukturen
- **Hardware-beschleunigte** Animationen

## Code-Qualität

- **Kotlin Coding Conventions** durchgängig angewendet
- **Null Safety** durch Kotlin Type System
- **Resource Externalisierung** (strings.xml, colors.xml)
- **Consistent Error Handling** mit Try-Catch Blöcken
