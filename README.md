# Simple Calculator Android

Robust, installable Android version of the simple calculator.

Built with HTML/CSS/JS and Capacitor for native Android packaging.

## Features
- Basic arithmetic operations
- Clear, operators, equals
- Dark theme, mobile-friendly

## Building the APK

Push to `main` triggers the GitHub Actions workflow which builds a debug APK.

Download the artifact from the Actions tab after the workflow completes.

### Local Development
```bash
npm install
npm run build
npx cap sync android
npx cap open android
```

Requires Android Studio / SDK for local builds.

## Installation
Sideload the generated `app-debug.apk` on your Android device (enable unknown sources).

App ID: `com.whatpopping.calculator`
