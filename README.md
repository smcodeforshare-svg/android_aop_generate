# My Basic App

A basic Android app that displays a simple HTML page using WebView.

## Project Structure

This is a standard Android project that can be built using Android Studio or command line Gradle.

## Building the APK

### Using Android Studio:
1. Open the project in Android Studio
2. Go to Build > Build Bundle(s) / APK(s) > Build APK(s)
3. The APK will be generated in `app/build/outputs/apk/`

### Using Command Line:
```bash
cd MyBasicApp
./gradlew assembleDebug  # For debug APK
./gradlew assembleRelease  # For release APK
```

## Features

- Displays HTML content in a WebView
- Simple and lightweight
- Minimum SDK: 21 (Android 5.0)
- Target SDK: 33 (Android 13)

## License

This is a basic demo app.