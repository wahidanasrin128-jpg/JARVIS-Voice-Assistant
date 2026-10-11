# JARVIS Android Project
Made by Arifin Wahid

This is a native Android WebView project.

Features:
- JARVIS voice UI
- Android JavaScript bridge
- Real flashlight control
- Camera opening
- Volume up/down
- Android Settings opening
- YouTube/Google opening
- Voice recognition where supported

Build:
1. Open this project in Android Studio or another Android Gradle build environment.
2. Sync Gradle.
3. Build > Build APK(s).
4. Install the generated APK on Android.

Important:
- Android Wi-Fi toggling is restricted on modern Android versions; this project does not pretend that a normal app can silently bypass those restrictions.
- Always-on "Hey Jarvis" needs a proper native foreground/background speech or wake-word implementation and user permission.
- The app requests microphone permission at runtime.
