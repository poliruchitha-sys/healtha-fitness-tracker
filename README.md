# 🏃 Health & Fitness Tracker

A simple Android application developed using **Kotlin and XML** to help users track their daily health and fitness activities.

The application allows users to monitor **steps, water intake, meals, and daily progress** in one place.

## 📱 Features

- 🚶 **Step Counter**
  - Tracks steps using the device's built-in step counter sensor.
  - Displays the current step count.

- 💧 **Water Tracker**
  - Add 250 ml of water with a single click.
  - Displays the total amount of water consumed.

- 🍎 **Meal Tracker**
  - Add meals throughout the day.
  - Displays the total number of meals.

- 📊 **Progress Dashboard**
  - View daily steps, water intake, and meals.
  - Displays progress toward daily health goals.

- 💾 **Local Data Storage**
  - Uses `SharedPreferences` to save tracking data.
  - Data is retained when the application is closed.

- 🔄 **Reset Daily Data**
  - Allows users to reset their tracked data.

- 🎯 **Daily Goals**
  - Step Goal: 10,000 steps
  - Water Goal: 2,000 ml
  - Meal Goal: 3 meals

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Kotlin | Android application development |
| XML | User interface design |
| Android Studio | Development environment |
| Android SDK | Android development |
| SharedPreferences | Local data storage |
| Android Step Counter Sensor | Step tracking |
| Material Design | UI components |

## 📂 Project Structure

```text
Health_fitness_tracker/
│
├── app/
│   └── src/
│       └── main/
│           │
│           ├── AndroidManifest.xml
│           │
│           ├── java/
│           │   └── com/example/health_fitness_tracker/
│           │       ├── MainActivity.kt
│           │       └── ProgressActivity.kt
│           │
│           └── res/
│               ├── layout/
│               │   ├── activity_main.xml
│               │   └── activity_progress.xml
│               │
│               ├── mipmap/
│               │   └── application icons
│               │
│               └── values/
│                   ├── colors.xml
│                   ├── strings.xml
│                   └── themes.xml
│
└── README.md
