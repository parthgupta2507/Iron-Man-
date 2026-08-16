# 🛡️ Iron Man — Advanced Motion Mechanics

> **An interactive Stark Industries HUD and Canvas Scratch-Reveal Experience built with Vanilla JavaScript, HTML5 Canvas, and Web Audio API.**

---

## 📌 Overview

**Iron Man — Advanced Motion Mechanics** is an interactive web-based HUD showcase inspired by Marvel's Mark LXXXV Nano-Tech suit. Built entirely with raw browser technologies—without external libraries, three.js, or heavy UI frameworks—it features a dual-layer canvas scratch-reveal engine, procedural audio synthesis, particle physics, and real-time 3D parallax viewport tilting.

---

## 🎯 Problem Statement

Traditional promotional pages and UI showcases are static, relying on heavy pre-rendered videos or bulky third-party libraries that slow down load times. This project demonstrates how native browser APIs can be leveraged to craft high-performance, cinematic, and interactive web experiences running at a smooth **60 FPS**.

---

## 🎨 Assets & Dataset

* **Base Layer Image:** `stark.jpg` — Civilian Tony Stark asset
* **Overlay Layer Image:** `nanoparticle.jpg` — Iron Man Mark LXXXV Armor asset
* **Audio Engine:** Dynamically generated in real-time using browser-native oscillators via the Web Audio API (no external `.mp3` or `.wav` dependencies)

---

## 🛠️ Tools & Technologies

* **Core Stack:** HTML5, CSS3, JavaScript (Vanilla ES6+)
* **Graphics & Rendering:** HTML5 Canvas API (Dual-canvas setup with `globalCompositeOperation`)
* **Audio Synthesis:** Web Audio API (Sine/Triangle wave oscillators & exponential gain ramps)
* **Typography:** Google Fonts (*Orbitron*, *Rajdhani*, *Share Tech Mono*)
* **Deployment:** GitHub Pages

---

## ⚙️ Technical Architecture & Methods

* **Dual-Canvas Scratch Engine:** Uses `globalCompositeOperation = 'source-over'` and `'source-in'` on an offscreen canvas to calculate smooth mouse cursor brush strokes that reveal the suit layer beneath.
* **Real-time Particle System:** Animates shockwaves, repulsor beams, and energy sparks using vector physics and exponential alpha decay.
* **Dynamic 3D Parallax Tilt:** Tracks normalized mouse coordinates relative to the viewport center to calculate live CSS `rotateX()` and `rotateY()` perspective transformations.
* **Procedural Sound Design:** Generates instant repulsor blast sound effects and frequency sweeps via Web Audio API gain ramps, eliminating latency and asset download overhead.

---

## 💡 Key Insights

* **Zero Dependencies:** Eliminating third-party libraries guarantees consistent **60 FPS** performance across modern devices.
* **Zero Network Latency for Audio:** Procedural audio synthesis removes network load times for instant user feedback.
* **High-DPI Optimization:** Incorporates `window.devicePixelRatio` scaling to prevent canvas blurriness on Retina displays.

---

## 💻 Interface & Output
* **Features:** Custom target crosshairs, dynamic Stark Industries HUD text overlay, interactive repulsor cannon blasts with screen-shake FX, and responsive tech specification cards.

---

## 🚀 How to Run

### Prerequisites
* Any modern web browser (*Google Chrome, Mozilla Firefox, Apple Safari, or Microsoft Edge*).

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/<your-repo-name>.git

### Linkdin: https://www.linkedin.com/in/parth-gupta-049802388/
### Author: Parth Gupta
