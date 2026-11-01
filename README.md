# Basket Compare (Android)

Build the APK on GitHub (no Android Studio needed):

1. Create a new empty repository on github.com (private is fine).
2. Upload everything from this folder, including the hidden `.github` folder.
3. Open the repo's **Actions** tab. The "Build APK" run starts by itself (about 3 to 5 minutes).
4. Open the finished run, scroll to **Artifacts**, download `basket-compare-apk`, and unzip it.
5. Send `app-debug.apk` to your phone, tap it, and allow installs from this source when asked.

Or build it in Android Studio: open this folder, let it sync, then Build > Build APK(s).

The app lives in `app/src/main/assets/index.html`. Prices are saved inside the app on the phone.
