# Tide 🌊

Tide is a simple Android water-intake tracker designed to make daily hydration tracking effortless.

Instead of manually calculating and logging every drink, Tide lets users set their bottle capacity and bodyweight, calculates a daily hydration target, and tracks progress through bottle refills.

## Features

* 💧 Daily water-intake goal
* 🥤 Bottle-based tracking
* 📊 Visual hydration progress
* ↩️ Undo the last bottle
* ⚙️ Edit your profile and hydration goal
* 💾 Local data persistence
* 📱 Android application built with a WebView-based interface

## Tech Stack

* Java
* Android SDK 34
* AndroidX AppCompat
* HTML
* CSS
* JavaScript
* Android WebView

## Project Structure

```text
TideAndroid/
├── app/
│   └── src/main/
│       ├── java/com/tide/app/
│       ├── assets/
│       └── res/
├── gradle/
├── build.gradle
├── settings.gradle
└── gradle.properties
```

## Requirements

* Android Studio
* Android SDK 34
* Java 8 or compatible JDK

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/tide-android.git
```

2. Open the project in Android Studio.

3. Let Gradle sync and download the required dependencies.

4. Connect an Android device or start an Android emulator.

5. Build and run the `app` module.

## How It Works

Tide asks for:

* Water bottle capacity
* Bodyweight

It then calculates a daily hydration target and converts the target into bottle-based progress.

Users can tap **Log a bottle** throughout the day to update their progress.

## Notes

The main application interface is implemented inside the Android app's WebView using local HTML, CSS, and JavaScript assets.

Google Fonts are loaded over the network when available, with system-font fallbacks.

## License

This project is currently published without a license. All rights reserved unless otherwise specified.
