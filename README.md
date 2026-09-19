# FocusGuard AI 🧠

An AI-powered study monitoring system that helps students
maintain focus by detecting sleepiness, face hiding, and
mobile phone usage in real time.

## 📌 Project Overview

FocusGuard AI uses computer vision and AI-based detection
to monitor student activities during study sessions.

The system uses a webcam to detect:
- Drowsiness / Sleepiness
- Face hiding
- Mobile phone usage

When distractions are detected, the system provides
audio alerts to help the student regain focus.

## ✨ Features

- Real-time webcam monitoring
- Face landmark detection
- Sleepiness detection
- Face hiding detection
- Mobile phone detection
- Audio alerts for detected distractions
- YOLO-based object detection

## 🛠️ Technologies Used

- Python
- OpenCV
- MediaPipe
- YOLOv8
- Ultralytics
- Pygame

## 📂 Project Structure

FocusGuard-AI/
│
├── app.py
├── alarm.mp3
├── faudio.mp3
├── paudio.mp3
├── face_landmarker.task
├── hand_landmarker.task
├── yolov8n.pt
├── .gitignore
└── README.md

## ⚙️ Installation

### 1. Clone the Repository
git clone https://github.com/vinaykedar1902/FocusGuard-AI.git

### 2. Navigate to the Project
cd FocusGuard-AI

### 3. Create a Virtual Environment
python -m venv venv

### 4. Activate Virtual Environment
Windows:
venv\Scripts\activate

### 5. Install Dependencies
pip install opencv-python
pip install mediapipe
pip install ultralytics
pip install pygame

### 6. Run the Application
python app.py

## 🧠 How It Works

1. The webcam captures live video.
2. Face landmarks are detected using MediaPipe.
3. Facial features are analyzed to identify
   possible sleepiness and face hiding.
4. YOLO detects mobile phone usage.
5. The system triggers audio alerts
   when distractions are detected.
