# MyAppStore

MyAppStore is a collection of Flutter applications. This project is built to practice and showcase Flutter development skills, including UI design, state management, and real-world app structure.

---

## Getting Started

Clone the repository:

git clone https://github.com/your-username/MyAppStore.git
cd MyAppStore

---

## Install Dependencies

flutter pub get

---

## Run Project

flutter run

---

## Flutter Doctor Status

Flutter (Channel stable, 3.41.4)
Windows 10 Pro (22H2)

Issues found:
- Dart path conflict
- Android toolchain missing
- Visual Studio not installed

---

## Fix Issues

### 1. Dart Path Conflict

Problem:
System is using Dart SDK outside Flutter.

Solution:
Add Flutter to PATH:

C:\flutter\bin

Remove or move:

C:\dart-sdk\bin

---

### 2. Android Toolchain Missing

Install Android Studio and required SDK tools.

Steps:
- Open Android Studio
- Go to SDK Manager
- Install:
  - Android SDK
  - Command-line Tools
  - Platform Tools

Set environment variable:

ANDROID_HOME = C:\Users\YourName\AppData\Local\Android\Sdk

---

### 3. Visual Studio (Optional)

Required for Windows apps only.

Download:
https://visualstudio.microsoft.com/downloads/

Install workload:
Desktop development with C++

---

## Useful Flutter Commands

flutter doctor
flutter doctor -v
flutter clean
flutter pub get
flutter run
flutter build apk
flutter build web

---

## Git Commands

git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/your-username/MyAppStore.git
git push -u origin main

---

## Project Structure

lib/
  main.dart
  screens/
  widgets/
  models/
  services/

---

## Notes

Make sure Flutter is correctly installed and environment variables are properly set before running the project.