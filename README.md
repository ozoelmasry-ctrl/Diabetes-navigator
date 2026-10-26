# Osrawy Diabetes Navigator — Android app project

This project packages the supplied HTML navigator inside a native Android WebView app. The HTML is bundled locally; JavaScript features work offline. Google Fonts may require an internet connection.

## Build an APK
1. Install Android Studio and the Android SDK (API 35 or let Android Studio install the requested SDK).
2. Open this folder in Android Studio.
3. Allow Gradle sync to finish.
4. Select **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
5. Android Studio will show a link to the generated APK (typically `app/build/outputs/apk/debug/app-debug.apk`).

## Notes
- Application ID: `com.osrawy.diabetes`
- Minimum Android version: Android 6.0 (API 23)
- This is a WebView wrapper for the supplied HTML, not a clinical validation of its treatment logic.
- Review all drug dosing, renal adjustments, brand/price information, and clinical recommendations against current authoritative guidance before clinical use.
