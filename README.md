✋ Hand Tracking Module – MediaPipe + OpenCV

A real-time hand tracking system built using MediaPipe and OpenCV.
This project provides a clean, reusable Python class (handDetector) that detects hands, extracts 21 hand landmarks, and returns their pixel positions for gesture control or computer vision applications.

The module runs efficiently on CPU and can be integrated into games, robotics, desktop automation tools, or gesture-based UIs.

🚀 Features

🔍 Detects one or multiple hands in real time

🎯 Tracks all 21 hand landmarks using MediaPipe

🖐️ Extracts positions of each landmark (x, y coordinates)

🧩 Reusable handDetector class for any CV project

⚡ Smooth FPS performance with OpenCV

📝 Simple API: findHands() and findPosition()

🎮 Ideal for hand-gesture based projects

🧠 How It Works

Captures frames from webcam

Converts BGR → RGB for MediaPipe processing

Detects hands via MediaPipe Hands model

Draws hand skeleton and connections

🛠 Technologies Used

Tech Stack:

Python

OpenCV

MediaPipe

Time module

Concepts Used:

Real-time computer vision

Landmark extraction

Gesture tracking

Frame processing

Drawing utilities

Collects landmark positions and maps them to pixel coordinates

Displays real-time FPS
