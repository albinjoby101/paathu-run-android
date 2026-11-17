# PAATHU RUN Android project

This is a native Android WebView wrapper around the current PAATHU RUN game.

## Build an APK
1. Open this folder (`PAATHU_RUN_Android`) in Android Studio.
2. Allow Android Studio to install the Android Gradle plugin and Android SDK platform 35 if prompted.
3. Wait for Gradle sync to finish.
4. Choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Android Studio will show the generated APK location (normally `app/build/outputs/apk/debug/app-debug.apk`).

The app uses its own WebView storage, separate from Chrome's website storage. It does not import the browser's test coins or hat ownership. The first install therefore starts with a clean wallet; coins collected and purchases made inside the app are saved on that device for later launches.

## Notes
- Internet permission is required because Three.js and the goat model are loaded from their existing HTTPS CDN URLs.
- Portrait orientation and immersive fullscreen are enabled.
- Package ID: `com.paathurun.game`
