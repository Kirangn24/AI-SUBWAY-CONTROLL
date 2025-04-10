<h1 align="center">🎮 AI-Powered Gesture-Based Subway Surfer Controller</h1>
<h3 align="center">Assistive Technology for Hand-Disabled Gamers</h3>

---

<h2>📘 Project Overview</h2>

<p>
The <strong>AI-Powered Gesture-Based Subway Surfer Controller</strong> is an innovative assistive technology project designed to empower individuals with hand disabilities to enjoy games like Subway Surfer using only head gestures and a webcam.
</p>

<p>
This Python-based system leverages <strong>Computer Vision</strong> and <strong>AI</strong> to convert real-time head movements into arrow key commands using:
<ul>
  <li><strong>OpenCV</strong> for video input</li>
  <li><strong>MediaPipe</strong> for face landmark detection</li>
  <li><strong>PyAutoGUI</strong> for keyboard simulation</li>
</ul>
</p>

---

<h2>🔍 How It Works</h2>

<ol>
  <li><strong>Camera Input:</strong> Webcam continuously captures video.</li>
  <li><strong>Head Detection:</strong> MediaPipe detects facial landmarks.</li>
  <li><strong>Zone Division:</strong> Camera feed is split into Up, Down, Left, Right zones.</li>
  <li><strong>Gesture Recognition:</strong>
    <ul>
      <li>Head Right → <code>Right Arrow</code></li>
      <li>Head Left → <code>Left Arrow</code></li>
      <li>Head Up → <code>Up Arrow</code> (Jump)</li>
      <li>Head Down → <code>Down Arrow</code> (Slide)</li>
    </ul>
  </li>
  <li><strong>Keyboard Simulation:</strong> PyAutoGUI simulates the matching keystroke.</li>
</ol>

---

<h2>✨ Key Features</h2>

<ul>
  <li>🎥 <strong>Real-Time Head Tracking</strong> – MediaPipe face mesh detection</li>
  <li>🧠 <strong>Gesture-Based Control</strong> – Head movements become in-game actions</li>
  <li>⌨️ <strong>Auto Key Simulation</strong> – PyAutoGUI sends arrow keys</li>
  <li>⚡ <strong>Lightweight & Efficient</strong> – Runs on standard laptops</li>
  <li>♿ <strong>Accessibility Focused</strong> – Hands-free gaming for all</li>
  <li>🚀 <strong>No Extra Hardware</strong> – Just a webcam needed</li>
</ul>

---

<h2>📦 Technologies Used</h2>

<ul>
  <li>Python 3.x</li>
  <li>OpenCV (cv2)</li>
  <li>MediaPipe</li>
  <li>PyAutoGUI</li>
</ul>

---

<h2>🔧 Future Enhancements</h2>

<ul>
  <li>🎮 Expand to support more games</li>
  <li>📱 Port to mobile for broader accessibility</li>
  <li>🗣️ Add voice control for extended actions</li>
  <li>🧠 ML-based gesture refinement for precision</li>
</ul>

---

<h3 align="center">🚀 Built with Love & AI – Empowering Inclusive Gaming Experiences 🎮</h3>
