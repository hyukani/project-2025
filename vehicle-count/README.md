# 🚗 DeepCount: Automatic Vehicle Counting System

## 📌 Project Overview

**DeepCount** is a computer vision-based system designed to automatically detect and count four-wheeled or more vehicles from video footage of roads. It aims to support traffic management without relying on physical sensors, offering a cost-effective and efficient alternative.

The system is capable of identifying moving vehicles using only video input, particularly on straight road segments. It utilizes a series of image processing techniques and tracking algorithms to achieve real-time, accurate vehicle counting.

### 🎯 Objectives
- Develop a video-based system to detect and count vehicles accurately.
- Eliminate the need for hardware sensors by relying on visual data alone.

---

## 🧠 Problem Statement
How can we design an accurate, automatic system to detect and count four-wheeled vehicles in real-time from road video footage without relying on physical sensors?

---

## ⚙️ Methodology

1. **Preprocessing**
   - Grayscale conversion
   - Gaussian Blur (7×7 kernel)
   - Region of Interest (ROI) masking

2. **Segmentation**
   - Background subtraction using MOG2 (Gaussian Mixture Model)
   - Morphological operations to clean object contours

3. **Detection & Tracking**
   - Contour detection for vehicle shape
   - Centroid tracking to identify movement
   - Euclidean distance used to maintain object ID

4. **Counting**
   - Vehicle counted when centroid crosses a predefined counting line

5. **Evaluation**
   - Metrics: Precision, Recall, F1-Score, Accuracy
   - Confusion matrix: TP, FP, FN

---

## 🔍 Challenges
- Conventional detection methods are not sensitive enough
- Require better preprocessing steps
- Advanced models like YOLO are more robust but complex
