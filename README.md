# Gatefront Android

This is the genuine Android Studio/Gradle application for Gatefront.

- Application ID: `com.brendanmolloy.gatefront`
- Version: `0.7.0` (`versionCode 700`)
- Minimum Android: 6.0 (API 23)
- Target Android: API 35
- Release signing alias: `gatefront`

Open this folder in Android Studio and run the `app` configuration. The release APK is built with `./gradlew assembleRelease`.

The release keystore is required to sign later updates with the same identity. Keep signing credentials outside source control and backed up securely.
