# Task Manager (Android)

Native Android app for creating and tracking personal tasks.

## Features
- Create, edit and delete tasks
- Sort by status, date or priority
- Data persisted locally so tasks survive app restarts

## Tech stack
- Java
- Android SDK
- SharedPreferences for persistence
- XML layouts
- Gradle

## Building and running
```bash
git clone https://github.com/CristiColtan/task-manager-android
```
Open the project in Android Studio, let Gradle sync, then run on an emulator 
or a connected device.

Or from the command line:
```bash
./gradlew assembleDebug
```

## Notes
Built to learn the Android activity/fragment lifecycle and local data 
persistence. [Detaliul tehnic cel mai interesant.]
