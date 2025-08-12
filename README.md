

# 👀 Face Detection with OpenCV

## 📌 Overview

This project is a **real-time face detection system** that uses your computer’s webcam to identify and highlight human faces.
It’s built using **Python** and **OpenCV**, with a **Haar Cascade classifier** for recognizing faces in video frames.

---

## 💡 How It Works

1. **Video Capture** 🎥

   * The program connects to your computer’s webcam and continuously captures video frames.

2. **Grayscale Conversion** ⚫⚪

   * Each frame is converted to grayscale for faster and more efficient processing.

3. **Face Detection** 🧑

   * The system uses a pre-trained **Haar Cascade model** (`haarcascade_frontalface_default.xml`) to scan for patterns that match human faces.

4. **Draw Bounding Boxes** 🟩

   * When a face is detected, a green rectangle is drawn around it in the live video feed.

5. **Live Display** 💻

   * The processed video with highlighted faces is displayed in real-time.
   * Press **`q`** to exit the program.

---

## 🎯 Key Features

* **Real-time detection** with minimal delay.
* **Pre-trained model** for reliable results.
* **Lightweight** and easy to run on most computers.
* Works with any standard webcam.

---

## 📂 Components

* **`FaceDtetctionCode.txt`** → Python script containing the detection logic.
* **`haarcascade_frontalface_default.xml`** → Pre-trained Haar Cascade model for frontal face detection.

---

## 🌐 Example Uses

* Attendance systems.
* Basic security cameras.
* Interactive art projects.
* Entry point for building facial recognition systems.


