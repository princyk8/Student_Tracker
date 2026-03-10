# Student Attendance Tracker (Flutter + Hive)

A modern **Flutter mobile application** that allows users to track subject attendance and store the data locally using the **Hive database**. The application features a clean UI with a gradient student profile header, subject attendance cards, and circular progress indicators.

---

## Features

- Add subjects with attendance percentage
- Store data locally using Hive database
- Display subjects using modern card UI
- Circular progress indicator for attendance
- Gradient student profile header
- Works completely offline
- Clean and responsive Material UI

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Flutter | Cross-platform UI framework |
| Dart | Programming language used in Flutter |
| Hive | Lightweight NoSQL local database |
| Android Studio | Development environment |
| GitHub | Version control and project hosting |

---

## Project Structure
lib
│
├── main.dart
├── database
│ └── hive_database.dart
├── screens
│ └── home_screen.dart
└── widgets
├── student_header.dart
└── subject_card.dart


---

## How It Works

1. The app starts with **MaterialApp**.
2. The **Student Header** displays student information.
3. Subjects are displayed using **custom card widgets**.
4. Pressing the **Floating Action Button (+)** opens a dialog.
5. The user enters subject name and attendance percentage.
6. Data is stored locally in the **Hive database**.
7. The subject list updates automatically.

---

## Installation

### 1. Clone the repository

### 2. Navigate to the project directory

### 3. Install dependencies

---

## Future Improvements

- Edit subject attendance
- Delete subjects
- Attendance statistics and charts
- Profile editing feature
- Cloud database integration

---
