# TicTacToe Android App

This repository contains an Android project for a TicTacToe app, along with release information exported by WebIntoApp. The Android source/project is under `android/`; the root `readme.txt` describes an app package named `com.mycompany.tictactoe`.

## Open and build

1. Clone the repository and open the `android/` project in Android Studio.
2. Allow Gradle to sync and install the Android SDK/build tools required by the project.
3. Run the app on an Android emulator or device, or build an APK from Android Studio/Gradle.

The exact Gradle tasks, minimum Android version, and app behavior are defined in the Android project files. This repository also contains `license.txt`; read it before copying or redistributing the project.

## Important credential note

The legacy `readme.txt` includes an app key and links to a third-party WebIntoApp account. Treat that key as potentially sensitive: revoke/rotate it with the provider if it is still active, and avoid publishing it in documentation. Do not use the third-party links as a required build step.

## Development

Keep Android Studio/Gradle configuration and app signing keys private. Never commit keystore files or signing passwords.
