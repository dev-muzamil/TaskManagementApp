📱 Task Management App

A simple and efficient task management application built with Flutter.
This app allows users to create, update, and delete tasks with a clean UI and native splash screen support.

🚀 Features

✔️ Add, update, and delete tasks

✔️ Persistent storage using Shared Preferences

✔️ Native Splash Screen using flutter_native_splash

✔️ Clean and minimal UI

✔️ Fast and lightweight

✔️ Cross-platform: Android, iOS, Web

📂 Project Structure

lib/
│── main.dart
│── screens/
│     └── home_screen.dart
│── widgets/
│     └── task_tile.dart
│── models/
│     └── task.dart
assets/
│── logo.png

🧩 Dependencies

This project uses the following dependencies:

dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.8
  shared_preferences: ^2.2.2

dev_dependencies:
  flutter_test:
    sdk: flutter
  flutter_lints: ^5.0.0
  flutter_native_splash: ^2.4.0

🖼 Splash Screen Configuration

Already included in your pubspec.yaml:

flutter_native_splash:
  color: "#5E35B1"
  image: assets/logo.png
  android: true
  ios: true
  web: true
  android_12:
    image: assets/logo.png
    icon_background_color: "#5E35B1"

To apply the splash screen, run:

>flutter pub get
>flutter pub run flutter_native_splash:create

🛠 Installation & Setup

1️⃣ Clone the repo

>git clone https://github.com/dev-muzamil/taskmanagementapp.git

2️⃣ Install dependencies

>flutter pub get

3️⃣ Run the splash setup

>flutter pub run flutter_native_splash:create

4️⃣ Run the app

>flutter run

🎨 Assets

Place your logo here:

assets/logo.png

Already included in pubspec:
assets:
  - assets/logo.png

🧑‍💻 About the Project

This project is created for learning Flutter fundamentals while building a practical Task Management application with persistence, UI design, and native splash screens.