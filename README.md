# Astra — Android UI Prototype

A two-screen Android prototype for practicing login and registration layouts and navigation.

## Technologies

Kotlin, Jetpack Compose, Material 3, Android Studio and Gradle, Navigation Compose.

## Features

- Login form with email and masked password fields.
- Registration form with name, email and masked password fields.
- Navigation between login and registration.
- Astra visual identity.

## Installation and execution

```bash
git clone https://github.com/Angel0208ia/astra-android-ui.git
cd astra-android-ui
```

Open **`Actividad 1/`**, not the repository root, in Android Studio. Install the SDK requested by Gradle (compile/target API 37) and allow dependency synchronization. The app supports Android API 24 and above. The checked-in Gradle daemon configuration requests JDK 25; Java source compatibility is 11. Use the wrapper and project toolchain rather than an arbitrary system Gradle version.

Run the `app` configuration on an emulator or device. To build on Windows from the Android project folder:

```powershell
.\gradlew.bat :app:assembleDebug
.\gradlew.bat :app:testDebugUnitTest
```

The debug APK is generated under `app/build/outputs/apk/debug/`.

## Scope and limitations

Beginner UI project. Login has a placeholder handler; registration returns to the previous screen. No accounts are created, no credentials are validated and no user information is stored. Do not enter real passwords.

The existing unit and instrumentation tests are template examples, not complete feature coverage. A full Android build requires Android SDK and toolchain downloads; it was not executed during the portfolio documentation audit. No application screenshots were present in the repository.

## Academic context

University project developed during Software Development Engineering studies. Author: Ángel Sebastián Mota Mora.
