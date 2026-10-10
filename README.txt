Supply Khata - Android project (WebView app, offline, data stays on the phone)

Option A: Android Studio
  1. Open this folder in Android Studio (File > Open).
  2. Wait for the Gradle sync to finish.
  3. Build > Build Bundle(s) / APK(s) > Build APK(s).
  4. The file is at app/build/outputs/apk/debug/app-debug.apk. Copy it to the phone and install it.

Option B: GitHub (no computer tools needed)
  1. Create a new GitHub repository and upload everything in this folder (keep the .github folder).
  2. Open the Actions tab, run "Build APK", and download SupplyKhata-apk from the finished run.
  3. Unzip it and install app-debug.apk on the phone (allow "install unknown apps" when asked).

The app screen is app/src/main/assets/index.html. The launcher icon is in app/src/main/res/mipmap-*.
