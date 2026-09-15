# Hisab Android APK

This is a small Android wrapper around the live Hisab web app:
https://hisab-by-melaku-sisay.netlify.app/

It keeps the existing web app as the source of truth. The Android app stores the web app's local data in its own WebView storage, so each installed copy has its own local expense data.

## Build an APK without Android Studio

1. Create a GitHub repository.
2. Upload this entire project.
3. Push to `main`.
4. Open the repository's **Actions** tab.
5. Run **Build Hisab APK** (or let the push workflow run).
6. Open the completed workflow run.
7. Under **Artifacts**, download `Hisab-APK`.
8. Inside it is `app-release.apk`.
9. Transfer the APK to Android and install it.

This APK is for direct sideloading/testing. A Play Store release needs signing, store metadata, and Google's current publishing requirements.
