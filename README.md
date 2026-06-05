# AI-Gym-Trainer-Project

# 🏋️ AI Gym Trainer

An AI-powered personal gym trainer that uses computer vision 
to detect body pose, count reps, and analyze workout form in real time.

---

## 👥 Team
- **Person A (Vision & Pipeline):** harshi-web-cyber
- **Person B (Frontend & UI):** Vaishnavi

---

## 🚀 Progress

### ✅ Person A — Completed
- Set up Python development environment
- Installed and configured OpenCV and MediaPipe
- Verified webcam access and video capture
- Successfully loaded MediaPipe Pose framework
- Implemented real-time body landmark detection
- Visualized 33 MediaPipe body landmarks
- Joint angle calculation for bicep curls
- Rep counter logic working in real time

### 🔄 Person A — In Progress
- Squat and deadlift detection
- Form correction feedback
- Flask server for data transmission to UI

### ⏳ Person A — Upcoming
- Knee, hip and spine angle calculation
- Multi exercise support
- Pose data transmission to backend

### ⏳ Person B — Upcoming
- Frontend UI dashboard
- Real time data display
- Exercise selection interface

---

## 🛠️ Tech Stack

| Person | Technologies |
|---|---|
| Person A | Python, OpenCV, MediaPipe, NumPy, Flask |
| Person B | JavaScript, React, Next.js |

---

## ⚙️ Setup & Run

```bash
# Create environment
conda create -n gymtrainer python=3.10
conda activate gymtrainer

# Install dependencies
pip install opencv-python mediapipe numpy flask

# Run
python pose_detection.py
```

---

## 📊 Status
> Person A: Pose detection and rep counter working ✅
> Person B: UI development upcoming ⏳

---


Environment setup completed and pose detection pipeline development is in progress.










