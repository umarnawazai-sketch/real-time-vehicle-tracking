# 🚗 Real-Time Vehicle Tracking & Counting with YOLO11

A real-time computer vision system for **vehicle detection, tracking, and directional counting** using **Ultralytics YOLO11** and **OpenCV**.

## ✨ Features

* 🎯 Vehicle detection using YOLO11
* 🆔 Unique vehicle tracking IDs
* 📏 Red & Blue virtual line-crossing detection
* ⬇️ Downward vehicle counting
* ⬆️ Upward vehicle counting
* 👁️ Real-time bounding boxes and tracking visualization

## 🧠 How It Works

```text
🎥 Input Video
      ↓
🤖 YOLO11 Detection
      ↓
🆔 Object Tracking
      ↓
📍 Center Point Detection
      ↓
📏 Line Crossing
      ↓
📊 Directional Counting
```

### Direction Logic

| Movement         | Direction   |
| ---------------- | ----------- |
| 🔴 Red → 🔵 Blue | ⬇️ Downward |
| 🔵 Blue → 🔴 Red | ⬆️ Upward   |

## 🛠️ Tech Stack

* **Python**
* **YOLO11 / Ultralytics**
* **OpenCV**
* **Pandas**
* **Jupyter Notebook**

## 📂 Project Structure

```text
real-time-vehicle-tracking/
│
├── test_videos/
│   └── 3.mp4
│
├── detect_track_count.ipynb
│
└── README.md
```

## 🚀 Installation

Install the required libraries:

```bash
pip install opencv-python pandas ultralytics
```

## ▶️ Usage

1. Place your traffic video inside the `test_videos` folder.
2. Open `detect_track_count.ipynb`.
3. Run the notebook cells.
4. The system will detect, track, and count vehicles based on their movement direction.

## 🎯 Concepts Demonstrated

* Object Detection
* Object Tracking
* Bounding Boxes
* Tracking IDs
* Line-Crossing Detection
* Direction Estimation
* Real-Time Video Processing

## 👨‍💻 Author

**Umar Nawaz**

BS Computer Science — Artificial Intelligence
Abdul Wali Khan University Mardan

---

⭐ **Detect • Track • Count • Analyze**