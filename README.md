# 🚍 Real-Time Bus Detection and Vehicle Counting System

This project was built to automate vehicle counting at college premises using real-time object detection and tracking techniques. It aims to replace manual vehicle counting, particularly for buses leaving the campus, with an efficient computer vision-based system.

### 📌 Project Overview

Due to limited access to live CCTV camera feeds, a video was manually recorded at the college gate, capturing the movement of vehicles—primarily buses—exiting the campus. The system uses YOLO (You Only Look Once) for detecting buses in each frame and assigns a unique ID to each detected vehicle using object tracking. As a bus crosses the defined exit boundary in the frame, the system updates the total vehicle count.

### 🔍 Key Features

- Detects buses in video footage using YOLO
- Assigns a unique ID to each bus for tracking
- Tracks movement frame-by-frame to prevent double-counting
- Increments vehicle count when a bus exits the college gate
- Provides real-time visual feedback with bounding boxes, IDs, and count overlay

### 🎯 Use Case

This system is designed to support colleges or institutions where manual vehicle logging is still practiced. It automates the counting process, ensures higher accuracy, and reduces human effort.


