# 🧠 AI Surveillance System – Real-Time People Counter

> A browser-based AI surveillance system that detects and counts people in real time using live camera feed and pre-recorded video — built using only HTML and client-side AI.

---

## 📌 Project Overview

The **AI Surveillance System – People Counter** is a lightweight, real-time people detection and counting application that runs entirely inside a web browser.

The system uses a pre-trained AI model to identify human presence in video frames and display live statistics, without requiring any backend server or cloud processing. All computation happens locally, making the system fast, portable, and privacy-friendly.

This project was developed as part of a **hackathon** to demonstrate the capabilities of modern browser-based artificial intelligence using minimal technologies.

---

## 🚀 Key Features

- ✅ Real-time people counting using live webcam feed  
- ✅ People detection from uploaded video files  
- ✅ AI-powered object detection (Person class only)  
- ✅ Live dashboard with dynamic statistics  
- ✅ Visual bounding boxes with confidence scores  
- ✅ Fully browser-based (no backend required)  
- ✅ Privacy-focused (no data leaves the device)

---

## 🧠 How It Works

1. The application captures video input from:
   - A live webcam stream, or
   - An uploaded video file
2. Each video frame is processed using a **pre-trained AI object detection model**
3. The model identifies human figures (`person` class)
4. Detected individuals are:
   - Counted in real time
   - Highlighted with bounding boxes
   - Logged and visualized on the dashboard

---

## 🛠 Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript**
- **TensorFlow.js**
- **COCO-SSD Object Detection Model**
- **Canvas API**
- **Chart.js**

> All technologies run entirely on the client side.

---

## 📂 Project Structure

```text
AI-Surveillance-System/
├── index.html
└── README.md
