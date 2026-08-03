# Contractor Miles - Automated IRS Mileage Tracker & Tax Deduction Planner

> Auto-detect business trips, swipe to categorize, and maximize tax deductions securely.

**Finance / Tax Utilities / Business Travel** built with Kotlin and modern Android development standards.

---

## 📖 How It Works

This application is built following **Clean Architecture**, **MVVM / MVI pattern**, and **Offline-First** principles.

### Architecture & System Modules
- **`:app` Module**: Application initialization, Hilt module graphs, dynamic provider bindings, and safe NavHost controllers.
- **`:core_ui` Module**: Premium financial M3 tokens (Deep Spruce Pine, Emerald, and Warm Gold), custom spring animation curves, swipe-deck layout wrappers, and chart coordinates.
- **`:feature_tracker` Module**: Foreground tracking services, FusedLocation wrappers, ActivityRecognition bounds receivers, and SQLite route buffers.
- **`:feature_swipe` Module**: Tinder-swipe card decks, motion event pointer trackers, active vehicle selector sheets, and quick-purpose modifiers.
- **`:feature_analytics` Module**: High-fidelity Compose Canvas charts (splines, stacked bars showing business vs personal splits), real-time tax deduction counters, and mileage progression meters.
- **`:feature_pro` Module**: Google Play Billing 6.x wrappers, dynamic premium tier widgets, paywall subscription pages, and cloud sync APIs.

### Required Android Permissions
- `android.permission.ACCESS_FINE_LOCATION (Essential for calculating exact route paths)`
- `android.permission.ACCESS_COARSE_LOCATION (Fallback coordinate mapping)`
- `android.permission.ACCESS_BACKGROUND_LOCATION (Crucial to intercept automatic drive starts under Android 13/14 background rules)`
- `com.google.android.gms.permission.ACTIVITY_RECOGNITION (Required to safely trigger vehicular transit detectors)`
- `android.permission.FOREGROUND_SERVICE_LOCATION (Required on Android 14+ to keep the active tracking session running continuously)`
- `android.permission.POST_NOTIFICATIONS (To prompt contractors immediately after a drive is processed)`
- `android.permission.INTERNET (Required for Google Maps APIs, geocoding coordinates, and AdMob services)`

---

## 📱 How to Use

### 1. Low Battery Auto Tracking Engine
High-fidelity, ultra-low-overhead automated background drive capturing pipeline.

### 2. Tinder Style Swipe Classification
An interactive card-stack swipe component allowing rapid sorting of unclassified drives.

### 3. Irs Deduction And Tax Calculator
Calculates real-time tax write-off metrics and tracks business-to-personal splits.

### 4. Irs Audit Ready Reports Exporter
Build high-resolution data sheets compiling every trip into standard IRS audit-proof logs.

### 5. Admob Monetization Layer



---

## 🚀 Key Features

- **Low Battery Auto Tracking Engine**: High-fidelity, ultra-low-overhead automated background drive capturing pipeline.
- **Tinder Style Swipe Classification**: An interactive card-stack swipe component allowing rapid sorting of unclassified drives.
- **Irs Deduction And Tax Calculator**: Calculates real-time tax write-off metrics and tracks business-to-personal splits.
- **Irs Audit Ready Reports Exporter**: Build high-resolution data sheets compiling every trip into standard IRS audit-proof logs.
- **Admob Monetization Layer**: 

---

## 🛠️ Tech Stack & Architecture

- **Language**: Kotlin
- **UI Framework**: Jetpack Compose (Material Design 3)
- **Architecture**: Clean Architecture + MVVM / MVI
- **Local Storage**: Room Database & DataStore
- **Async Operations**: Kotlin Coroutines & StateFlow
- **Build System**: Gradle Kotlin DSL
- **Min SDK**: 26 | **Target SDK**: 34

---

## 💻 Getting Started

### Prerequisites
- Android Studio Ladybug (2024.2.1+) or newer
- JDK 17+
- Android SDK 34+

### Building & Running
1. Clone the repository:
   ```bash
   git clone https://github.com/hsinidev/Contractor-Miles.git
   cd Contractor-Miles
   ```
2. Open the project in Android Studio.
3. Sync Gradle dependencies and run on an Android device or emulator.

---

## 📬 Contact & Support

Created and maintained by **Hsini**.

- **Website**: [hsini.dev](https://hsini.dev)
- **Email**: [contact@hsini.dev](mailto:contact@hsini.dev)
- **GitHub**: [@hsinidev](https://github.com/hsinidev)

---

© 2026 [hsini.dev](https://hsini.dev). All rights reserved.
