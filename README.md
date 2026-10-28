# Finger Fruit Slice 🍏🍉💣

An interactive, browser-based **Fruit Slice** game built using vanilla HTML5, CSS3, JavaScript, HTML5 Canvas, and **MediaPipe Hand Landmarker** (Computer Vision). Players can use their index finger via webcam tracking or standard mouse/touch input to slice fruits, build high combos, avoid dangerous bombs, and collect special power-ups!

---

## ✨ Features

- **Real-Time Hand Tracking:** Powered by Google's MediaPipe Tasks Vision, allowing you to play naturally using just your index finger in front of your webcam.
- **Mouse & Touch Fallback Support:** Fully playable using standard mouse swipes or touchscreen gestures if no webcam is available.
- **Dynamic Difficulty:** Scales progressively from **Easy** to **Insane** as your score increases (featuring faster speeds, higher spawn rates, and increased challenges).
- **Special Items & Power-Ups:**
  - **Golden Fruits (★):** Worth a massive 50 bonus points.
  - **Bombs (💣):** Costs a life unless blocked by a shield.
  - **Power-Ups:** Collect shields, slow-motion timers, and double points (2x).
- **Built-in Web Audio API:** Immersive, synthesized sound effects generated entirely in code with zero external audio dependencies.
- **Persistent Local Storage:** Automatically saves your high scores and lifetime game statistics.

---

## 🚀 How to Run Locally

Because this game relies on WebRTC camera permissions and ES modules (`import`), it requires a local web server to run correctly (avoid opening `index.html` directly via the `file://` protocol).

1. Clone or download this repository.
2. Open the project folder in **Visual Studio Code** or your preferred code editor.
3. Start a local development server:
   - **Using VS Code:** Install the **Live Server** extension, right-click `index.html`, and select **"Open with Live Server"**.
4. Allow webcam access when prompted, show your index finger to the camera, and click **Start Game**!

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+ Modules)
- **Graphics & Rendering:** HTML5 Canvas API
- **AI & Computer Vision:** MediaPipe Hands (`@mediapipe/tasks-vision`)
- **Audio:** Web Audio API

---

## 👤 Author

Made by [nilsantra535-oss](https://github.com/nilsantra535-oss)