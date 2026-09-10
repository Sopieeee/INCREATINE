# INCREATINE
A simple Android water-intake tracker for creatine taking users using bottle-based daily hydration tracking.


Detailed Summary - 
Increatine 🌊
Increatine is a simple Android water-intake tracker designed to make daily hydration tracking effortless.

Instead of manually calculating and logging every drink, Increatine lets users set their bottle capacity and bodyweight, calculates a daily hydration target, and tracks progress through bottle refills.

Features
💧 Daily water-intake goal

🥤 Bottle-based tracking

📊 Visual hydration progress

↩️ Undo the last bottle

⚙️ Edit your profile and hydration goal

💾 Local data persistence

📱 Android application built with a WebView-based interface

Tech Stack
Java

Android SDK 34

AndroidX AppCompat

HTML

CSS

JavaScript

Android WebView

Project Structure
Plaintext
IncreatineAndroid/
├── app/
│   └── src/main/
│       ├── java/com/increatine/app/
│       ├── assets/
│       └── res/
├── gradle/
├── build.gradle
├── settings.gradle
└── gradle.properties
Requirements
Android Studio

Android SDK 34

Java 8 or compatible JDK

Getting Started
Clone the repository:

Bash
git clone https://github.com/YOUR-USERNAME/increatine-android.git
Open the project in Android Studio.

Let Gradle sync and download the required dependencies.

Connect an Android device or start an Android emulator.

Build and run the app module.

How It Works
Increatine asks for:

Water bottle capacity

Bodyweight

It then calculates a daily hydration target and converts the target into bottle-based progress.

Users can tap Log a bottle throughout the day to update their progress.

Notes
The main application interface is implemented inside the Android app's WebView using local HTML, CSS, and JavaScript assets.

Google Fonts are loaded over the network when available, with system-font fallbacks.

License
This project is currently published without a license. All rights reserved unless otherwise specified.
