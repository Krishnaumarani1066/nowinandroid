# Moonwing (NammaSkills App)

[![Platform](https://img.shields.io/badge/Platform-Android-brightgreen.svg)](https://developer.android.com)
[![Language](https://img.shields.io/badge/Language-Kotlin-purple.svg)](https://kotlinlang.org)
[![Compose](https://img.shields.io/badge/UI-Jetpack%20Compose-blue.svg)](https://developer.android.com/jetpack/compose)
[![License](https://img.shields.io/badge/License-Apache%202.0-lightgrey.svg)](LICENSE)

**Moonwing** (Namma Skills) is a robust skills and learning platform built specifically for the students of **Sri Venkateshwara College of Engineering (SVCE), Bengaluru**. Developed using cutting-edge Android technologies, the platform aims to bridge the gap between academic curriculum and trending industry skills, enabling students to continuously upskill.

This repository is maintained at:  
👉 **[Krishnakumarani1066/nowinandroid](https://github.com/Krishnakumarani1066/nowinandroid)**

---

## 📱 Core Features

*   **Skill Exploration:** Discover and browse trending industry-relevant skills, articles, and curated courses.
*   **Custom Interest Feed:** Follow specific tech stacks or academic topics to build a personalized dashboard.
*   **Smart Notifications:** Instant alerts keep students updated the moment new content or learning materials drop.
*   **Bookmarks System:** Save resources dynamically to read later, featuring persistent offline capabilities.

---

## 🛠️ Architecture & Tech Stack

Moonwing is heavily inspired by modern Android architecture guidelines (based on Google's *Now in Android* sample architecture), emphasizing a highly modularized, multi-module codebase built for scalability.

*   **UI Layer:** [Jetpack Compose](https://developer.android.com/jetpack/compose) — Declarative, modern UI development.
*   **Design Tokens:** **Material 3 (M3)** — Sleek, intuitive components with dynamic color capabilities.
*   **Dependency Injection:** [Hilt](https://developer.android.com/training/dependency-injection/hilt-android) — Scoped dependency trees for clean testing and separation of concerns.
*   **Local Caching:** [Room Database](https://developer.android.com/training/data-storage/room) — Offline-first capability ensuring bookmarks and feeds stay accessible without an active internet connection.
*   **Network Engine:** [Retrofit](https://square.github.io/retrofit/) & Serialization — Safe HTTP communication for data syncing.
*   **Backend & Analytics (Firebase Integration):**
    *   **Authentication:** Seamless student authentication and profiling.
    *   **Analytics:** Tracking learning trends within SVCE to improve resource allocation.
    *   **Crashlytics:** Proactive real-time bug tracking to optimize stability.

---

## 🚀 Development Setup

Follow these straightforward steps to set up a local copy of Moonwing for development and testing:

### Prerequisites
*   **Android Studio** (Latest Stable Release)
*   **JDK 17+** configured in Android Studio
*   An Android Emulator or physical device configured with **API level 26+**

### Step-by-Step Installation

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/Krishnakumarani1066/nowinandroid.git](https://github.com/Krishnakumarani1066/nowinandroid.git)
    cd nowinandroid
    📱 Now in Android – Setup & Build Guide
🚀 Import the Project
Open Android Studio.

Navigate to:

File → Open

Select the cloned project root directory.
Allow Gradle to sync completely.
(Initial setup may take a few minutes depending on internet speed and dependencies.)
🔥 Firebase Configuration
Step 1: Create Firebase Android App
Open Firebase Console
Create or select your Firebase project.
Add an Android application with the following package name:
com.google.samples.apps.nowinandroid
Step 2: Download Configuration File
Download the generated google-services.json file.
Place the file inside the following directory:
app/google-services.json
▶️ Running the Application
Select Build Variant
Open:
View → Tool Windows → Build Variants
Set the active variant to:
demoDebug
Run the App
Connect an Android device or start an emulator.
Click the Run ▶️ button in Android Studio.
The application will build and install automatically.
📦 Project Build Variants
Variant	Environment	Purpose
demoDebug	Development & Staging	Full logging enabled, optimized for local development and debugging
demoRelease	Production Release	Minified with R8/ProGuard, obfuscated, and optimized for public deployment
📸 Screenshots

Application UI previews and screenshots will be added soon.

🤝 Contributing

Contributions from students and open-source enthusiasts are welcome.

Steps to Contribute
# Fork the repository

# Create a feature branch
git checkout -b feature/AmazingFeature

# Commit your changes
git commit -m "Add some AmazingFeature"

# Push to GitHub
git push origin feature/AmazingFeature

Then create a Pull Request for review.

👨‍💻 Maintainers & Credits

Developed and maintained by the tech ecosystem at:

Institution: Sri Venkateshwara College of Engineering
Based on architectural concepts inspired by Google’s Now in Android framework.

GitHub Repository:

Krishnakumarani1066/nowinandroid

📄 License

This project is distributed under the Apache License Version 2.0.

For more details, refer to the LICENSE file located in the project root directory.
