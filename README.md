# THISODA Rental Android App

Android WebView wrapper for the hosted THISODA Rental Management System.

App URL: https://jonathantj.shinyapps.io/THISODA/

## Build APK using GitHub

1. Create a new GitHub repository, for example `THISODA-Android`.
2. Upload all files and folders in this project to the repository root.
3. Open the repository's **Actions** tab.
4. Select **Build THISODA Android APK**.
5. Click **Run workflow** (or wait for the push build to finish).
6. Open the completed workflow run.
7. Under **Artifacts**, download `THISODA-Rental-APK`.
8. Extract the downloaded artifact ZIP. It contains `app-debug.apk`.
9. Transfer `app-debug.apk` to the Android phone and install it. Allow installation from that source if Android asks.

## App details

- Display name: THISODA Rental
- Package ID: com.thisoda.rental
- Version: 1.0
- Minimum Android: 6.0 (API 23)
- Hosted system remains online; an internet connection is required.

## Notes

This project is a WebView client. User accounts, permissions, billing and rental data remain controlled by the hosted Shiny application. File upload and download support is included, but should be tested with the actual Shiny workflows and Android devices.
