# Notebook App - Flutter Web

A simple note-taking application with local data storage using Flutter + Hive.

## Features
- Add notes
- Edit notes
- Delete notes
- Data persistence on app refresh

## Project Structure
```typescript
├── lib/                      → Main application code
│   ├── main.dart             → Entry point
│   ├── models/
│   │   ├── note.dart         → Note model
│   │   └── note.g.dart       → Generated Hive adapter
│   ├── screens/
│   │   └── home_screen.dart  → Main screen
│   ├── services/
│   │   └── note_storage.dart → Hive operations
│   └── widgets/
│       ├── note_card.dart    → Note card widget
│       └── note_dialog.dart  → Edit dialog
```

## Prerequisites
How to install and run the application:
- Install Flutter SDK
- Install Git
- Install Dart SDK
- Install Visual Studio Code

Clone the repository or open the project folder "notebook_app" in Visual Studio Code

To clone the repository:
```sh
git clone https://github.com/liatsoii/notebook-app.git
```
## Install dependencies

Execute these commands sequentially in the terminal.

```sh
flutter pub get
```
```sh
flutter pub run build_runner build
или
git run build_runner build
```

Run the application

```sh
flutter run -d chrome
```
## Technologies Used in Notebook App

Core Technologies:

Flutter (v3.0+) – cross-platform development framework.

Dart (v3.0+) – programming language for Flutter.

Local Storage:

Hive (^2.2.3) – NoSQL database for local storage.

Hive Flutter (^1.1.0) – Hive integration with Flutter.

Hive Generator (^2.0.0) – model adapters generation.

Dependencies:

path_provider (^2.1.2) – filesystem access.

cupertino_icons (^1.0.8) – iOS-style icons.

Dev Dependencies:

build_runner (^2.4.6) – code generation (for Hive).

flutter_test – testing (included in Flutter SDK).

flutter_launcher_icons (^0.13.1) – app icon generation.

Tools and Supporting Technologies:

Material Design – Google's design system (used in UI).

ValueListenableBuilder – reactive UI updates with Hive changes.

AlertDialog & TextField – standard Flutter widgets for forms.

Build and Run:

Flutter Web – browser support (--web-renderer html).

Live Server (VS Code) – local server for web version testing.

Version Control:

Git – source code management (.gitignore included).

| Technology         | Role in Project                                                                 |
|--------------------|-------------------------------------------------------------------------------|
| **Flutter**        | Main framework for cross-platform UI development                        |
| **Dart**           | Programming language for business logic                            |
| **Hive**           | Fast local storage for notes (NoSQL database)                              |
| **Hive Flutter**   | Hive integration with Flutter app                                         |
| **Hive Generator** | Auto-generation of data model adapters                                    |
| **path_provider**  | Filesystem access for Hive operations                                     |
| **Material Design**| Design system for UI (buttons, cards, dialogs)           |
| **ValueListenableBuilder** | Reactive UI updates when Hive data changes                 |
| **build_runner**   | Code generation for Hive model operations                              |
| **Flutter Web**    | Browser support (Chrome))                          |
| **Live Server**    | Local server for web version testing in VS Code                        |

## Developed with ❤️ for convenient note-taking
