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
git clone https://github.com/Sopieeee/INCREATINE.git
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

<img width="627" height="1280" alt="image" src="https://github.com/user-attachments/assets/e5e34bf4-5961-4ab3-a2ad-640d1434a566" />

<img width="629" height="1280" alt="image" src="https://github.com/user-attachments/assets/9e57132d-066a-4a0e-b32a-22b20119bff9" />

<img width="628" height="1280" alt="image" src="https://github.com/user-attachments/assets/3c426951-df75-4a43-bdb3-ffd31bf8dca8" />


