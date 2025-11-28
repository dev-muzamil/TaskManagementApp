# Task Management App

A simple Flutter task management application that demonstrates local persistence, a clean UI, and platform splash screen configuration.

**Repository:** https://github.com/dev-muzamil/TaskManagementApp

**Current Branch:** `main`

**Quick Links:** `lib/main.dart`, `lib/screens/home_screen.dart`, `lib/models/task.dart`, `lib/widgets/task_tile.dart`

**Getting Started**
- **Prerequisites:** `Flutter` >= 3.x, `Dart` SDK, and a platform toolchain for Android/iOS if you plan to build native apps.
- **Clone:** `git clone https://github.com/dev-muzamil/TaskManagementApp.git`
- **Open project:** `cd taskmanagementapp`
- **Install deps:** `flutter pub get`
- **Run (debug):** `flutter run`

**Build**
- **Android (APK):** `flutter build apk --release`
- **Android (App bundle):** `flutter build appbundle`
- **iOS:** `flutter build ios` (requires macOS + Xcode)
- **Web:** `flutter build web`

**Features**
- **Add / Remove tasks:** Create, complete, and remove simple tasks.
- **Local persistence:** Uses `shared_preferences` to persist tasks locally.
- **Responsive UI:** Basic, clean UI with reusable widgets in `lib/widgets`.
- **Custom splash screen:** Integrated `flutter_native_splash` and generated splash assets for Android, iOS, and Web.

**Project Structure**
- **`lib/`**: Application source code.
- **`lib/main.dart`**: App entrypoint.
- **`lib/models/task.dart`**: Task model definition.
- **`lib/screens/home_screen.dart`**: Home screen with task list and add UI.
- **`lib/widgets/task_tile.dart`**: Reusable task tile widget.
- **`assets/`**: App assets such as `assets/logo.png` used for splash and branding.

**Important Files**
- **`pubspec.yaml`**: Project dependencies and assets (includes `flutter_native_splash` and `shared_preferences`).
- **`README.md`**: This file.

**Dependencies (high-level)**
- `shared_preferences` — local persistence for simple data storage.
- `flutter_native_splash` — generates native splash screen assets and config.

**Splash Screen Notes**
- The native splash is configured in `pubspec.yaml` under `flutter_native_splash` and uses `assets/logo.png` as the splash image.
- To regenerate splash assets after editing `pubspec.yaml` or the logo, run:

```
flutter pub run flutter_native_splash:create
```

**Testing**
- Run unit/widget tests: `flutter test`

**Contribution**
- Feel free to open issues or submit pull requests.
- Keep changes focused and include a short description in your PR.

**License & Contact**
- This repository currently has no explicit license file. Add a `LICENSE` if you want to open-source under a specific license.
- Contact: `dev-muzamil` (see GitHub profile)

**Notes / Next Steps**
- Add screenshots under `assets/` and reference them here for better README UI.
- Add CI (GitHub Actions) for tests and building release artifacts.

Thank you for using the Task Management App — reach out if you want help adding features or CI.
