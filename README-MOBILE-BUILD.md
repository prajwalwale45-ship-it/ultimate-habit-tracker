# Mobile-only APK build

This project includes GitHub Actions workflows so the Android APK can be built in the cloud without Android Studio on your phone.

## Phone steps
1. Create/sign in to GitHub.
2. Create a new repository.
3. Upload the project files so `package.json`, `capacitor.config.json`, `www/`, and `.github/workflows/` are at the repository root.
4. Open the **Actions** tab.
5. Select **Build Android APK** and tap **Run workflow**.
6. Wait for the workflow to finish.
7. Open the completed workflow run and download the artifact named **Ultimate-Habit-Study-Tracker-APK**.
8. Extract the artifact ZIP and install `app-debug.apk` on Android.

The debug APK is for personal installation/testing. Publishing to Google Play requires a properly signed release build and Play App Bundle setup.
