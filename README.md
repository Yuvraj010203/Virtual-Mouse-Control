# 💻 Virtual Mouse Control using Hand Gestures

This project allows users to control mouse operations using **hand gestures** detected via webcam. Built using **OpenCV** and **MediaPipe**, the system recognizes hand landmarks and maps specific gestures to actions like moving the cursor, clicking, scrolling, holding, and controlling volume.

---

## 📅 Project Overview

A **gesture-based virtual mouse** system that utilizes computer vision and real-time hand tracking to simulate mouse and keyboard actions. The application runs with a simple GUI built with **Tkinter** for selecting gesture modes.

---

## 🛠️ Tech Stack & Libraries

- **Languages**: Python
- **Libraries**:
  - `opencv-python`
  - `mediapipe`
  - `pyautogui`
  - `numpy`
  - `tkinter`
  - `pycaw` (for audio control)
  - `ctypes`, `comtypes` (for system volume API)

---

## 📝 Features

- 30+ Hand Gestures
-  Cursor movement
- Single and double click support
- Volume control
- Scroll functionality
- Mouse drag/hold support
- Real-time gesture response
- GUI to toggle between modes:
  - Click / Volume
  - Scroll / Hold

---

## Modes Available

### 1. Click Mode
- **Single Click**: Thumb + Index finger touch
- **Double Click**: Thumb + Ring finger touch

### 2. Volume Mode
- **Volume Up**: Thumb + Index finger close
- **Volume Down**: Thumb + Middle finger close

### 3. Scroll / Hold Mode
- **Scroll Up/Down**: Thumb + Middle/Pinky finger gesture
- **Mouse Hold**: Thumb + Index finger close
