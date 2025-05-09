# 🖐️ Gesture Control

This project allows users to control certain operations using hand gestures captured via webcam. Built using Python and OpenCV, it supports two main functionalities:

## 📸 1. Screenshot Capture - `screensort_gesture.py`

Take a screenshot by simply showing a **specific hand gesture** in front of the camera.

### 🔧 How it works:
- Uses a webcam feed to detect hand landmarks.
- When the system detects the gesture (e.g., thumb and index finger touching), it captures a screenshot.
- Saves the image to your local system.

### ✅ Requirements:
- Python
- OpenCV
- `pyautogui`
- `mediapipe`

## 🎥 2. Camera Control - `camera_control.py`

Use hand gestures to control webcam features like:
- Zoom In/Out
- Pause/Resume Video
- Switch between webcam modes (optional)

### 🔧 How it works:
- Detects hand movement and interprets it as a command.
- Based on finger positions or distance between fingers, appropriate action is triggered.

### ✅ Requirements:
- Python
- OpenCV
- `mediapipe`

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/nehakumari2003/gesture-control.git
cd gesture-control

