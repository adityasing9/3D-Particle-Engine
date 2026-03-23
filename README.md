<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF00FF,100:00E5FF&height=200&section=header&text=Ultimate%203D%20Particle%20Engine&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/WebGL-Three.js-black?style=for-the-badge&logo=three.js" />
  <img src="https://img.shields.io/badge/AI-MediaPipe-blue?style=for-the-badge&logo=google" />
  <img src="https://img.shields.io/badge/Audio-WebAudio%20API-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Frontend-HTML/CSS/JS-yellow?style=for-the-badge&logo=javascript" />
  <img src="https://img.shields.io/badge/Deployment-Single%20HTML-red?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,git,github" />
</p>

---
Click Here 👉 **[Live Demo Available !](https://adityasing9.github.io/3D-Particle-Engine/v8)**

# 🌌 Advanced Visualizer Engine
An **insanely interactive, audio-reactive 3D particle simulation** built completely within a single, dependency-free HTML document. It uses machine learning for hand tracking and spatial web APIs for audio synchronization.

---

## 🎮 How to Play / Instructions

1. **Open the Live Demo** link above.
2. **Grant Permissions:** Click "Allow" when your browser requests Camera and Microphone access. *(Required for Hand Tracking and Audio to work!)*
3. **Bring the Noise!** 
   - Click the **Mic** button to visualize your voice or room audio.
   - Click the **Screen Share** button to visualize audio from a YouTube/Spotify tab.
   - Or just **Upload an MP3** to play local music using the on-screen UI.
4. **Use the Force (Hand Tracking):**
   - 👆 **Push Particles:** Point your index finger directly at the camera to repel particles in 3D space.
   - 🤚 **Air Swipe:** Drag your open hand left/right/up/down to rotate the entire simulation.
   - 🤏 **Color Pinch:** Snap your thumb and index finger together to instantly randomize the neon color gradients!
5. **Change Shapes:** Use the UI panel to instantly snap the particles into shapes like a DNA Helix, Saturn, or Fireworks.

---

## ✨ Features

### ✋ AI Hand Tracking (MediaPipe)
- **Air Swipe:** Spin the entire particle universe 360 degrees globally by dragging your finger mid-air.
- **Color Pinch:** Snap your thumb and index finger together to instantly randomize neon gradients.
- **Forcefield Physics:** Push your finger directly into the particles to physically repel them away natively in 3D. 

### 🎵 Universal Audio Matrix
- **Room Mic:** Reacts to live conversation and ambient noise.
- **System Audio Hook:** Natively visualizes background desktop tabs (Spotify, YouTube) via browser screen-share loopbacks.
- **Offline MP3 Engine:** Included on-screen UI player to upload and perfectly sync local music tracks.
- **HTTP URL Streaming:** Dynamically wraps internet radio streams with a CORS proxy to instantly visualize external broadcast links.

### 💠 Mathematical Geometries
- Massive **20,000 pristine particle simulation** locked at a crisp 60 FPS.
- Instantly snap to 9 custom procedural shapes: 
  *Möbius Strip, Galaxy Spiral, DNA Helix, Torus Knot, Fireworks, Hearts, Flowers, Saturn, Buddha.*

---

## 🛠 Tech Stack

Frontend: HTML5 • CSS3 • Vanilla JavaScript  
Graphics Pipeline: True WebGL via Three.js (r128)  
AI Machine Vision: Google MediaPipe SDK  
Signal Processing: Native WebAudio API Matrix  

---

## 📂 Project Structure

```bash
particle-engine/
│
├── index.html        # The massive, single-file God-Mode app
└── README.md         # Documentation
```
*(Yes, entirely contained in one single file!)*

---

## ⚙️ Local Setup

```bash
git clone https://github.com/adityasing9/Particle-Engine.git  

cd Particle-Engine  
```

### Execution
There are absolutely zero `npm`, `node`, or build steps required. 
```text
Open: index.html  
```
*Note: Make sure to click "Allow" when the browser requests Webcam and Microphone permissions, or the AI and Audio features will not load!*

---

## 🚀 System Breakdown

## 🧠 AI Tracking Engine
- Loads MediaPipe Hands models via JavaScript CDN.
- Extracts spatial XYZ coordinates from the index finger tip.
- Translates those coordinates to apply `Math.atan2` Euler rotation on the ThreeJS Group.

---

## ⚡ Signal Processing
- Captures Byte Frequency Data (128 array length).
- Specifically isolates Bass amplitudes (`index < 10`) to explicitly trigger geometry scaling/pumping.
- Isolates Treble amplitudes to push noise-based XYZ scatter formulas per-particle.

---

## 👨‍💻 Author

Aditya Singh  
https://github.com/adityasing9  

---

<p align="center">
  ⭐ If you like this exact project, give the repo a star!
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF00FF,100:00E5FF&height=120&section=footer"/>
</p>
