# Omni Tools Android wrapper

This project packages the deployed Omni Tools PWA as a native Android WebView app.

PWA URL:
https://ais-pre-lz3uikxqxdnrgwip5j2d5q-94928389705.asia-east1.run.app

## Build in Android Studio
1. Install Android Studio and Android SDK Platform 35.
2. Open this folder as an existing Gradle project.
3. Let Gradle sync and install missing Android components if prompted.
4. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
5. The debug APK will be under `app/build/outputs/apk/debug/`.

For a Play Store release, use Build > Generate Signed Bundle / APK and create a release keystore.
