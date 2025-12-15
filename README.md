# Flutter Week 2 – Data Management and Persistent Storage

## Project Overview
This Flutter application demonstrates basic state management and local persistent storage, developed as part of Week 2 internship task.  
The main goal of this project is to understand and implement:

- State management using `setState`
- Persistent data storage using `SharedPreferences`
- Simple user interface to manage counter and tasks

---

## Features Implemented

### 1. Counter App
- A counter with **increment (+)** and **decrement (-)** buttons.
- The counter value is **stored locally** using SharedPreferences.
- When the app is closed and reopened, the counter **retrieves the last saved value** automatically.

### 2. To-Do List App
- Users can **add new tasks** using a TextField.
- Tasks are displayed in a **ListView**.
- All tasks are **saved locally** using SharedPreferences.
- On reopening the app, previously added tasks **are loaded automatically**.

---

## Technologies Used
- **Flutter** – for app development and UI
- **Dart** – programming language
- **SharedPreferences** – for local persistent storage

---

## How It Works

1. **State Management**:
   - `setState()` is used to update the UI when the counter changes or a new task is added.
2. **Persistent Storage**:
   - Counter value is saved using `SharedPreferences.setInt()` and retrieved using `SharedPreferences.getInt()`.
   - Task list is saved using `SharedPreferences.setStringList()` and retrieved using `SharedPreferences.getStringList()`.
3. **UI Flow**:
   - Counter section at the top
   - To-Do list section below with input field, add button, and list display

---

## Notes
- The application logic is fully implemented according to internship requirements.
- While emulator/Gradle issues may affect local runtime testing, the **code is complete, structured properly, and ready to run** on any configured Android device or emulator.
- Folder hierarchy is maintained as required by Flutter projects:  
