# 🔮 Gesture-Controlled Particle Sphere

A real-time, interactive 3D particle sphere built entirely with Vanilla JavaScript, HTML, and CSS. The application utilizes **MediaPipe Hands** AI to track your hand gestures through your webcam, allowing you to manipulate a sphere made of thousands of particles in a highly responsive and physics-driven environment.

[![GitHub Pages](https://img.shields.io/badge/Deployed-GitHub_Pages-blue?style=flat-square&logo=github)](#)
[![MediaPipe](https://img.shields.io/badge/AI-MediaPipe-orange?style=flat-square)](#)
[![Vanilla JS](https://img.shields.io/badge/Made_with-Vanilla_JS-yellow?style=flat-square&logo=javascript)](#)

---

## ✨ Features & Gesture Controls

This project features a robust physics engine and AI tracking to translate physical hand gestures into stunning visual effects:

| Gesture | Action |
| :--- | :--- |
| **🖐️ Single Hand** | **Move & Rotate:** The sphere follows your hand's position and calculates your wrist roll to rotate the 3D structure. |
| **🤏 Pinch & Hold** | **Charge & Explode:** Bring your thumb and index finger together to build up charge. Release when the ring is full to trigger a radial particle explosion before reforming. |
| **👐 Two Hands** | **Scale:** Spread both hands apart to grow the sphere, or bring them close together to shrink it. |
| **✌️ Finger Count** | **Color Shift:** The system counts the number of extended fingers across your hands to smoothly transition the sphere's color hue. |

- **Webcam Background:** Features a sleek UI toggle to show or hide your mirrored webcam feed in the background.
- **Clean UI:** A minimalist, dark-themed aesthetic prioritizing performance and visual impact.

## 🚀 Live Demo
**[View Live Demo](https://sanskritig007.github.io/practiclesphere/)**

## 🛠️ Tech Stack
- **HTML5 & CSS3:** For a responsive, full-screen canvas layout and clean UI styling.
- **Vanilla JavaScript:** All core logic, physics, and state management (Zero UI frameworks used).
- **Google MediaPipe (`@mediapipe/hands`):** For performant, in-browser machine learning hand tracking.

## 💻 Running Locally

Because this project uses the webcam (which requires a secure context or `localhost`), you need to run it through a local server. 

### Prerequisites
- Any modern web browser (Chrome, Edge, Firefox).
- A working webcam.

### Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/sanskritig007/practiclesphere.git
   cd practiclesphere
   ```
2. Start a local server. You can use any of the following methods:
   - **VS Code:** Install the "Live Server" extension, right-click `index.html`, and select *Open with Live Server*.
   - **Node.js:** Run `npx serve` in the terminal.
   - **Python:** Run `python -m http.server 8000` in the terminal.
3. Open the provided localhost link in your browser.
4. **Allow webcam access** when prompted. Wait a few seconds for the AI models to initialize, and start interacting!

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/sanskritig007/practiclesphere/issues).

---
*Built with ❤️ exploring the intersection of AI, Physics, and Web Graphics.*
