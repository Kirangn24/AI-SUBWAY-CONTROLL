🎮 AI-Powered Gesture-Based Subway Surfer Controller
A hands-free, AI-driven game controller that empowers hand-disabled gamers to play Subway Surfer using only head movements via webcam.

📘 Project Overview
This project transforms head gestures into game controls using computer vision and AI, allowing individuals with hand disabilities to enjoy games without a keyboard or mouse.

Built with Python, OpenCV, MediaPipe, and PyAutoGUI, the system detects head movement in real-time and simulates keyboard inputs for intuitive, hands-free gameplay.

🔍 How It Works
🎥 Webcam Input – Captures real-time video of the player's face.

🧠 Head Tracking – MediaPipe detects facial landmarks to identify head orientation.

🕹️ Gesture Zones – The screen is split into four directional zones.

⌨️ Simulated Controls – PyAutoGUI triggers arrow keys based on detected gestures:

Left head tilt → Left Arrow

Right head tilt → Right Arrow

Head up → Up Arrow (Jump)

Head down → Down Arrow (Slide)

✨ Features
Real-time, accurate head movement tracking

Fully hands-free control system

Easy setup—just Python + Webcam

No external sensors or devices required

Accessibility-first design for inclusive gaming

📦 Tech Stack
Python 3.x

OpenCV

MediaPipe

PyAutoGUI

🚀 Future Enhancements
Expand to more games and controls

Add gesture calibration UI

Integrate voice commands

Port to mobile or browser environments
