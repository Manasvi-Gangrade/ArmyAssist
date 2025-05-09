
# ArmyAssist: AI-Powered Command & Surveillance Demo

## 🔥 Project Overview
**ArmyAssist** is a multifunctional AI-powered defense prototype integrating:
- 🎙️ Voice-controlled command system
- 📊 Real-time military-style dashboard
- 🎯 Object detection for surveillance
- 🛡️ Secure face authentication
- 🗺️ Map-based troop simulation

---

## 🚀 Features

### 1. Voice-Controlled Army Assistant
- “Open mission dashboard” → launches Streamlit UI
- “Show troop status” → displays dummy status
- “Initiate surveillance” → triggers object detection
- “Initiate red alert” → plays alarm sound

### 2. Streamlit-Based Dashboard
- Troop status display (dummy)
- Emergency alert panel
- Live object detection feed (OpenCV)
- Threat level indicator

### 3. Object Detection (OpenCV + YOLO)
- Real-time detection of soldier, weapon, vehicle
- Bounding boxes with labels on video feed

### 4. Face Recognition Security
- Use face_recognition for admin access
- Add your image as `assets/admin.jpg`

### 5. Leaflet Map Troop Movement (Optional Extension)
- Display live simulated troop locations

---

## 🧠 Tech Stack
- Python 3
- speech_recognition, pyttsx3
- streamlit (UI)
- opencv-python (Surveillance)
- face_recognition (Access Control)
- YOLOv8 (Object Detection)
- threading, os, time

---

## 📁 Folder Structure
```
ArmyAssist/
├── app/
│   └── main.py               # Main orchestrator (Streamlit + Voice)
├── modules/
│   ├── voice_assistant.py    # Voice commands
│   ├── face_auth.py          # Face recognition
│   └── object_detection.py   # YOLOv8 detection
├── assets/
│   └── admin.jpg             # Your face for authentication
├── static/
│   └── alert.mp3             # Red alert sound
└── README.md
```

---

## 🧪 How to Run
```bash
pip install -r requirements.txt
python app/main.py
```

Make sure `assets/admin.jpg` is added before running.

---
