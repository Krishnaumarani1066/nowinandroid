# Moonwing (NammaSkills App)

[![Platform](https://img.shields.io/badge/Platform-Android-brightgreen.svg)](https://developer.android.com)
[![Language](https://img.shields.io/badge/Language-Kotlin-purple.svg)](https://kotlinlang.org)
[![Compose](https://img.shields.io/badge/UI-Jetpack%20Compose-blue.svg)](https://developer.android.com/jetpack/compose)
[![License](https://img.shields.io/badge/License-Apache%202.0-lightgrey.svg)](LICENSE)

**Moonwing** (formerly Namma Skills) is a dedicated skills and learning platform built exclusively for the students of **Sri Venkateshwara College of Engineering (SVCE), Bengaluru**. Designed to bridge the gap between academic learning and industry trends, the app empowers students to discover, track, and master modern skills.

---

## 📱 Features

- **Skill Discovery:** Browse the latest industry-relevant skills, courses, and learning content.
- **Personalized Feed:** Follow specific topics of interest to customize your learning dashboard.
- **Instant Notifications:** Stay updated with real-time alerts whenever new content or learning materials are published.
- **Bookmarks:** Save articles, tutorials, and resources to read later, even offline.

---

## 🛠️ Tech Stack & Architecture

Moonwing is built using modern Android development practices, leveraging a robust and scalable architecture.

*   **UI Layer:** [Jetpack Compose](https://developer.android.com/jetpack/compose) – Android’s modern toolkit for building native UI using declarative APIs.
*   **Design System:** Material 3 – Adhering to the latest Material Design guidelines for a sleek, modern look.
*   **Dependency Injection:** [Hilt](https://developer.android.com/training/dependency-injection/hilt-android) – For clean, modular, and testable code.
*   **Local Persistence:** [Room Database](https://developer.android.com/training/data-storage/room) – Caches data locally for offline support and bookmark management.
*   **Networking:** [Retrofit](https://square.github.io/retrofit/) – Handles Type-safe HTTP client requests for fetching remote learning content.
*   **Backend Integration:** [Firebase](https://firebase.google.com/)
    *   **Authentication:** Secure student login and onboarding.
    *   **Analytics:** To understand user engagement and improve content delivery.
    *   **Crashlytics:** For real-time crash reporting and stability monitoring.

---

## 🚀 Getting Started & Development Setup

Follow these steps to get a local copy of the project up and running on your machine.

### Prerequisites
*   Android Studio (Latest stable version recommended)
*   JDK 17 or higher
*   An Android Device or Emulator running API 26+

### Setup Instructions

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/your-username/moonwing.git](https://github.com/your-username/moonwing.git)
    cd moonwing
