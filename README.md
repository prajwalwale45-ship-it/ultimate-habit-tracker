# Ultimate Habit & Study Tracker — Android + iPhone

This project wraps the supplied Version 10 HTML app in Capacitor so the same app can be built for Android and iOS.

## Requirements
- Node.js LTS
- Android Studio + Android SDK for Android
- macOS + Xcode for iPhone/iOS builds

## Setup
1. Extract this ZIP.
2. Open a terminal in the project folder.
3. Run: `npm install`
4. Run: `npx cap add android`
5. Run: `npx cap add ios` (macOS only)
6. Run: `npx cap sync`

## Build/open
- Android: `npx cap open android` then Build APK in Android Studio.
- iPhone: `npx cap open ios` then build/sign in Xcode.

The app itself is in `www/index.html`. No app functionality was intentionally changed; the supplied Version 10 HTML is used as the web layer.
