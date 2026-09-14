# Gatefront Android

This is a genuine Android Studio/Gradle application built around the Gatefront 0.6.0 game source.

- Application ID: `com.brendanmolloy.gatefront`
- Version: `0.6.0` (`versionCode 600`)
- Minimum Android: 6.0 (API 23)
- Target Android: API 35
- Release signing alias: `gatefront`

Open this folder in Android Studio and run the `app` configuration. The release APK is built with `./gradlew assembleRelease`.

The included release keystore is required to sign later updates with the same identity. Its password is `Gatefront060!`; keep it private and backed up.
