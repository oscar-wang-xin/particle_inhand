# 🤖 PARTICLE INHAND

<div align="center">

**Real-time 3D Interactive Particle System Based on Gesture Recognition**  
*Open your palm to spread particles, pinch fingers to gather particles*

[![GitHub stars](https://img.shields.io/github/stars/oscarwang164/particle-inhand?style=for-the-badge)](https://github.com/oscarwang164/particle-inhand/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/oscarwang164/particle-inhand?style=for-the-badge)](https://github.com/oscarwang164/particle-inhand/network)
[![MIT License](https://img.shields.io/github/license/oscarwang164/particle-inhand?style=for-the-badge)](LICENSE)

[📖 User Guide](#user-guide) • [🎯 Features](#features) • [🚀 Quick Start](#quick-start)

</div>

---

## 📋 Table of Contents

- [✨ Project Introduction](#project-introduction)
- [🎬 Screenshots](#screenshots)
- [🚀 Quick Start](#quick-start)
- [🎮 User Guide](#user-guide)
- [🎯 Features](#features)
- [🛠️ Technology Stack](#technology-stack)
- [🎨 Visual Design](#visual-design)
- [🔧 Development & Deployment](#development--deployment)
- [📄 License](#license)
- [🙏 Acknowledgments](#acknowledgments)
- [📞 Contact](#contact)

---

## ✨ Project Introduction

This is an innovative 3D particle interaction system that combines advanced computer vision technology and 3D rendering technology. Through MediaPipe gesture recognition, users can control the behavior of 15,000 particles in real-time with gestures, creating stunning visual effects.

### Key Features

- ✋ **Gesture Control** - Real-time gesture tracking, particles respond dynamically to gestures
- 🎨 **6 Particle Models** - Heart, Saturn, Flower, Fireworks, Butterfly, Flame
- 🚀 **High-Performance Rendering** - 60fps smooth operation of 15,000 particles
- 🌟 **Sci-fi Visual Effects** - Futuristic UI design, stunning light and shadow effects

---

## 🎬 Screenshots

<div align="center">

**Main Interface**
<img src="screenshot/2026-01-09_2135004.png" alt="Particle System Main Interface" width="600">

<p><em>Main interface showing particle controls and gesture recognition status</em></p>

**Particle Animation**
<img src="screenshot/2026-01-09_2134002.png" alt="Particle Animation Effect" width="600">

<p><em>Real-time particle animation with gesture control</em></p>

</div>

---

## 🚀 Quick Start

### System Requirements

| Requirement | Description |
|-------------|-------------|
| **Browser** | Chrome 88+, Firefox 85+, Safari 14+ |
| **Hardware** | Modern graphics card supporting WebGL |
| **Permissions** | Camera access permissions (for gesture recognition) |
| **Network** | HTTPS or localhost environment |

### Running the Project

```bash
# Method 1: Open directly in browser
# Double-click index.html or drag it into the browser window

# Method 2: Use local server (recommended)
# Python 3
python -m http.server 8000

# Node.js (requires http-server)
npx http-server

# Then visit http://localhost:8000 in your browser
```

---

## 🎮 User Guide

### Gesture Control

| Gesture | Effect | Icon |
|---------|--------|------|
| 🖐️ Open Palm | Spread Particles | 🔄 |
| 🤏 Pinch Fingers | Gather Particles | 🎯 |
| 👉 Move Left/Right | Control Rotation Direction | ↻ |
| ⚡ Quick Open/Close 3 Times | Trigger Easter Egg | 🎉 |

### Mouse Control

- **Left Click Drag**: Rotate particle view
- **Scroll Wheel**: Zoom particle size

### Panel Control

- **Model Selection**: Switch between 6 particle shapes
- **Color Adjustment**: Real-time particle color adjustment
- **Size Adjustment**: Control particle size (0.01-0.3)

---

## 🎯 Features

### 🌟 Core Features

#### 6 Particle Models

| Model | Description |
|-------|-------------|
| ❤️ Heart | Heart-shaped parametric equation |
| 🪐 Saturn | Sphere + rotating ring |
| 🌸 Flower | Rose line equation |
| 🎆 Fireworks | Spherical explosion effect |
| 🦋 Butterfly | Butterfly curve |
| 🔥 Flame | Dense bottom diffusion |

#### Gesture Recognition System

- Real-time MediaPipe gesture tracking
- Smooth particle response animation
- Intelligent easter egg trigger mechanism

#### Interactive Control

- Mouse drag rotation
- Scroll wheel zoom control
- Real-time parameter adjustment

### ⚡ Technical Highlights

- 🚀 **High-Performance Rendering**: 15,000 particles at 60fps real-time rendering
- 🎨 **Visual Effects**: Additive blending glow effects
- 🔧 **Modular Architecture**: Clear code organization structure
- 📱 **Responsive Design**: Adaptive to different screen sizes
- 🛡️ **Error Handling**: Comprehensive exception handling mechanism

---

## 🛠️ Technology Stack

<div align="center">

| Technology | Purpose |
|------------|---------|
| HTML5/CSS3/JavaScript (ES6+) | Frontend Framework |
| Three.js r128 | 3D Rendering |
| MediaPipe Hands API | Gesture Recognition |
| Custom CSS | Style Design |
| Orbitron (Google Fonts) | Typography |

</div>

---

## 🎨 Visual Design

### Sci-fi Theme

- **Color Scheme**: Cyan (#00FFFF) tech-inspired colors
- **Background Effects**: 3D cosmic grid + dynamic halos
- **Animation Effects**: Smooth particle transition animations
- **UI Design**: Futuristic control panels

### Performance Optimization

- **LOD System**: Distance culling optimization
- **Memory Management**: Efficient object lifecycle
- **Rendering Optimization**: Throttling and debouncing techniques

---

## 🔧 Development & Deployment

### Development Environment

```bash
# Clone the project
git clone https://github.com/oscarwang164/particle-inhand.git
cd particle-inhand

# Edit index.html directly
# Use modern browser developer tools for debugging
```

### Deployment Instructions

Since this is a pure frontend project, static files can be deployed directly to any web server.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- [Three.js](https://threejs.org/) - Powerful 3D rendering engine
- [MediaPipe](https://mediapipe.dev/) - Google's machine learning framework
- [Google Fonts](https://fonts.google.com/) - Quality font resources

---

## 📞 Contact

- **Project Maintainer**: Oscar Wang
- **Email**: [164938@qq.com](mailto:164938@qq.com)
- **GitHub**: [@oscarwang164](https://github.com/oscarwang164)

---

## 🌐 Language Switch

- English: [README-en.md](README-en.md)
- 简体中文: [README.md](README.md)

---

<div align="center">

**🎉 Enjoy the amazing experience of gesture-controlled 3D particles!**

⭐ If this project helps you, please give it a star!

</div>