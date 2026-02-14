# ⚽ Football Match Analysis System

An end-to-end computer vision pipeline that analyzes football match footage to detect players, track movement, estimate speed, and generate visual insights. This project demonstrates real-world video analytics using deep learning and tracking algorithms.

---

## 🚀 Features

- Player, referee, and ball detection using YOLO
- Multi-object tracking with ByteTrack
- Camera motion estimation
- Player speed and distance calculation
- Ball trajectory interpolation
- Tactical position transformation (top-down view)
- Annotated video generation
- Robust pipeline with debugging and safety checks

---

## 🧠 What This Project Shows

This project highlights:

- Real-world video processing pipeline design
- Computer vision engineering
- Handling noisy detections
- Performance debugging
- Working with large video data
- End-to-end ML system thinking

---

## 🛠️ Tech Stack

- Python
- OpenCV
- Ultralytics YOLO
- Supervision (ByteTrack)
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab

---

## 📂 Project Workflow

1. Load match video
2. Detect players and ball
3. Track objects across frames
4. Estimate camera motion
5. Transform positions to field coordinates
6. Compute speed and distance
7. Draw annotations
8. Save analyzed video

---

## 📊 Output

The system generates:

- Annotated match video
- Movement overlays
- Speed statistics
- Tracking visualization

---

## ▶️ How to Run

Install dependencies:

```bash
pip install ultralytics supervision opencv-python numpy pandas scikit-learn matplotlib
