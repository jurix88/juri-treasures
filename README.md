# JuriTreasures 💎

Eine Flutter-App zum Verwalten deiner Antiquitäten-Sammlung.

## Features

- 📱 Responsive Design mit Material 3
- 🎨 Dark Mode Support
- 💾 Lokale Datenspeicherung
- ✨ Elegante Animationen
- 🏆 Benutzerfreundliche Oberfläche

## Installation

### Voraussetzungen
- Flutter SDK (>=3.0.0)
- Android SDK oder iOS SDK
- Dart

### Setup

```bash
# Repository klonen
git clone https://github.com/jurix88/juri-treasures.git
cd juri-treasures

# Dependencies installieren
flutter pub get

# App starten
flutter run
```

## APK Bauen

### Lokal mit Android Studio
1. Android Studio öffnen
2. Projekt laden
3. Build → Build APK(s) oder Generate Signed Bundle / APK

### Mit Kommandozeile

Debug-Version:
```bash
flutter build apk --debug
```

Release-Version:
```bash
flutter build apk --release
```

### Automatisch mit GitHub Actions

Die APK wird automatisch gebaut, wenn du in den `main` Branch pushst.
Die fertige APK findest du unter "Actions" → neuester Workflow → "Artifacts".

## Struktur

```
lib/
├── main.dart          # Hauptprogramm & Splash Screen
├── models/            # Datenmodelle
├── services/          # Business Logic
└── screens/           # UI Screens
```

## Lizenz

MIT License

## Autor

jurix88