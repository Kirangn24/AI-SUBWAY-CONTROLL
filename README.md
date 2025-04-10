🎮 AI-Powered Gesture-Based Subway Surfer Controller for Hand-Disabled Players
📘 Full Project Description
The AI-Powered Gesture-Based Subway Surfer Controller is an innovative assistive technology solution designed to empower individuals with hand disabilities to enjoy computer games such as Subway Surfer without the need for traditional input devices like a keyboard or mouse.

This project leverages Computer Vision and Artificial Intelligence to convert head movements into game control commands using only a webcam. Built using Python, the system integrates OpenCV for video capture and image processing, MediaPipe for real-time face and head landmark detection, and PyAutoGUI for simulating keypress events.

The primary goal of this project is to make fast-paced games more accessible, inclusive, and fun for players with physical limitations by providing a hands-free gaming experience.

🔍 How It Works
Camera Input: The webcam continuously captures the user's video stream.

Head Detection: MediaPipe detects facial landmarks and identifies the position of the user's head in real-time.

Screen Zone Division: The live camera frame is virtually split into four zones — up, down, left, and right.

Gesture Recognition: Based on the movement of the head into a specific zone:

Moving right → triggers the Right Arrow key.

Moving left → triggers the Left Arrow key.

Moving up → triggers the Up Arrow key (for jumping).

Moving down → triggers the Down Arrow key (for sliding).

Simulated Keypress: PyAutoGUI sends the corresponding keyboard command to control the character in the game.

✨ Key Features
🎥 Real-Time Head Tracking
Uses MediaPipe's efficient face mesh detection to track head position with high accuracy.

🧠 Gesture-Based Interaction
Converts intuitive head movements into actual in-game actions.

⌨️ Automatic Keyboard Simulation
Seamlessly triggers keyboard arrow keys using PyAutoGUI based on user gestures.

⚡ Lightweight & Efficient
Designed to run smoothly on standard laptops and PCs with minimal setup.

♿ Accessibility-Focused
Aimed at gamers who cannot use their hands or traditional input devices.

🚀 No External Hardware Required
Only needs a built-in or external webcam—no fancy sensors or controllers.

📦 Technologies & Libraries Used
Python 3.x – Core programming language for logic and integration.

OpenCV (cv2) – For video capture, image manipulation, and frame processing.

MediaPipe – Google’s ML pipeline for detecting face mesh and tracking head position.

PyAutoGUI – For simulating keypress events based on gesture recognition.

🔧 Potential Use Cases & Future Enhancements
🎮 Extending to other games that use arrow key inputs.

📱 Porting to mobile platforms for broader accessibility.

🤖 Adding voice control or additional gestures for more game actions.

🧠 Enhancing gesture accuracy using machine learning models for better user experience.

Let me know if you’d like a polished version of this for a project report, portfolio website, or academic submission — I can format it accordingly!
