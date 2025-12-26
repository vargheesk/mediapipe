# 🎭 AI Face & Hand Tracking Studio

![Python](https://img.shields.io/badge/Python-3.11.8-blue?logo=python&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0.10.13-teal?logo=google&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-red?logo=opencv&logoColor=white)

A powerful real-time computer vision project utilizing **Google's MediaPipe** framework. This project performs high-speed face detection, creates detailed face meshes, and tracks hand movements via webcam video streams.

---

## ✨ Features

| Module | Icon | Description |
| :--- | :---: | :--- |
| **Hand Tracking** | 🖐️ | Real-time detection of hand landmarks (21 points) with skeletal connections. |
| **Face Detection** | 👤 | Fast face detection with bounding boxes and confidence scores. |
| **Face Mesh** | 🕸️ | High-fidelity face tracking with 468 distinct 3D landmarks. |

---

## 🛠️ Tech Stack & Prerequisites

Based on your environment configuration, ensure you have the following installed:

* **Language:** Python `3.11.8`
* **Core Library:** MediaPipe `0.10.13`
* **Computer Vision:** OpenCV (cv2)

---

## 🚀 Installation

1.  **Clone the repository** (if applicable) or download the `.ipynb` files.

2.  **Install Dependencies**
    Run the following command in your terminal to install the exact version of MediaPipe used in this project:

    ```bash
    pip install mediapipe==0.10.13 opencv-python numpy
    ```

---

## 📂 Project Structure

```text
📦 Project Root
 ┣ 📜 Face_landmarks.ipynb   # 👤 Face Detection & 🕸️ Face Mesh logic
 ┗ 📜 Hand.ipynb             # 🖐️ Hand Tracking & Landmark drawing