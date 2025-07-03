<div align="center">

# ✋ Virtual Hand Keyboard

Type using hand gestures — no physical keyboard needed!  
Built with Python, OpenCV, and cvzone for a seamless touchless typing experience.

<img src="https://skillicons.dev/icons?i=python,numpy,opencv,git,github" alt="tech stack" />

</div>

---

## 📌 Overview

**Virtual Hand Keyboard** is a gesture-controlled keyboard powered by your webcam.  
You can type letters by pointing at virtual keys using your index finger and "click" by pinching (index + middle finger).

---

## 🎯 How It Works

- 📷 Uses your **webcam** to detect hand in real-time
- ✋ Tracks **index finger** to detect which key you're pointing at
- 👌 When **index + middle finger pinch** → triggers key press
- 💬 Simulates actual typing using `pynput`
- 🔙 Special key `<` works as backspace

---

## 🧠 Tech Stack & Libraries

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,numpy,opencv,git,github" alt="tech stack" />
</p>

| Library     | Purpose                                 |
|-------------|------------------------------------------|
| `cvzone`    | Hand tracking (built on MediaPipe)       |
| `opencv`    | Video capture and visual UI              |
| `numpy`     | Coordinate & distance calculations       |
| `pynput`    | Simulate key presses                     |
| `python`    | Core programming language                |

---

## 🎥 Demo Video

Watch the virtual keyboard in action:  
▶️ [Click to view the demo video](./assets/demo_video.MOV)

> Or open it manually: `assets/demo_video.MOV`

---

## 🛠️ Installation & Run

### 1. Clone the repo

```bash
git clone https://github.com/YOUR_USERNAME/Virtual-Hand-Keyboard.git
cd Virtual-Hand-Keyboard
