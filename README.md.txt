# FlamApp Edge Viewer

This project is developed as part of the **FlamApp R&D Internship Assignment**.  
It demonstrates an **Edge Detection and Visualization Pipeline** across different platforms.

---

## 📱 Android (Java + OpenCV)
- Uses Android + OpenCV for real-time **Canny Edge Detection**
- Displays processed frames on a live camera view
- Written in `MainActivity.java`

---

## ⚙️ Native (C++ - JNI)
- Provides a native interface for processing frames via `edge_processor.cpp`
- Simulates efficient frame conversion and edge detection
- Uses OpenCV functions for grayscale conversion and Canny edges

---

## 🎨 OpenGL Renderer (C++)
- Implements a stub OpenGL ES renderer in `Renderer.cpp`
- Simulates basic GPU-based rendering for processed frames

---

## 🌐 Web Viewer (TypeScript + HTML)
- Simple simulation of edge visualization in browser using `Canvas API`
- Files: `index.html`, `main.ts`, and `sample_frame.png`

---

## 🧠 Tools & Technologies
- **Languages:** Java, C++, TypeScript  
- **Frameworks:** OpenCV, OpenGL, Android SDK  
- **Version Control:** GitHub  
- **IDE Used:** Visual Studio Code / Android Studio  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Bakkiyashree/flamapp-edge-viewer.git