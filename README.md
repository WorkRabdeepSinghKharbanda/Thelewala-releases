# ThelaWala — Android early access

ThelaWala shows street vendors (thelas) that are live near you. This repo only hosts the **early-access Android APK** until the app is approved on Google Play and the App Store.

**Download:** open the [latest release](../../releases/latest) and get `ThelaWala-production-1.0.0+1.apk`.

## Install
1. Download the APK on your Android phone.
2. Allow "Install unknown apps" for your browser or Files app when asked.
3. If Play Protect warns, tap **Install anyway** (the build is not from the Play Store yet).
4. Open ThelaWala and sign in with your phone number.

## Notes
- Early-access build with a temporary signing key. When the Play Store version arrives, uninstall this one first.
- The app uses the live service; payments inside the app are real.
- Verify your download: `shasum -a 256 ThelaWala-production-1.0.0+1.apk` must match the SHA-256 in the release notes.
- Website: https://thelewala.vercel.app/download
