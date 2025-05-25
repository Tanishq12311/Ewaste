

```markdown
# ♻️ E-Waste Tracker App

An Android application to help users track and categorize electronic waste (e-waste) by adding entries with names, categories, and images. Built using **Java** in **Android Studio** with **SQLite** for local storage.

---

## 📱 Features

- Simple user login/entry screen
- Add e-waste entries with:
  - Name
  - Category (via dropdown)
  - Image (from gallery)
- Store and retrieve data using SQLite
- Image paths are saved for previewing later

---

## 🛠 Tech Stack

- **Language:** Java
- **Framework:** Android SDK
- **Database:** SQLite (`SQLiteOpenHelper`)
- **UI Design:** XML Layouts
- **Image Handling:** `MediaStore`, Intents

---

## 🏗️ Project Structure

```

com.example.ewastetracker/
├── MainActivity.java
├── AddEwasteActivity.java
├── DBHelper.java
├── res/
│   └── layout/
│       ├── activity\_main.xml
│       └── activity\_add.xml
└── AndroidManifest.xml

````

---

## ⚙️ Permissions Required

```xml
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
````

> For Android 10+ (API 29+), scoped storage is used via `MediaStore`.

---

🚀 Getting Started
 Prerequisites

* Android Studio Bumblebee or newer
* Java 8 or higher
* Android SDK API level 29+

 Steps

1. Clone or download this repo
2. Open the project in Android Studio
3. Build and run on an emulator or physical device

---

📌 Future Improvements

* List view for saved entries
* Edit/delete e-waste items
* Firebase integration for cloud sync
* Dark mode UI

---

## 👤 Author
Tanishq Singh




