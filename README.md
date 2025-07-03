<div align="center">

# ✋ Virtual Hand Keyboard

Type in the air using your fingers — a fully touchless virtual keyboard using AI & Computer Vision!

<img src="https://skillicons.dev/icons?i=python,opencv,github" alt="tech stack" />

</div>

---

## 📌 Overview

This project allows users to simulate typing on a virtual keyboard using **hand gestures** tracked by their **webcam**.

You point your **index finger** at a key, and "click" it by bringing your **middle finger close** — all without touching a real keyboard.

---

## 🎯 How It Works

- 🖐 Detects your hand using `cvzone` (MediaPipe under the hood)
- 👆 Tracks the tip of your index finger to know where you're pointing
- 👌 Detects a click when index and middle fingertips are close
- ⌨️ Displays a virtual keyboard and types using `pynput`
- 🧠 Shows real-time typed text on screen
- 🔙 Supports Backspace with `<` button

---

## 🧠 Tech Stack & Libraries

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,opencv,github" alt="tech stack" />
</p>

| Library     | Role                                          |
|-------------|-----------------------------------------------|
| `cvzone`    | Hand tracking, bounding boxes, utility tools  |
| `opencv`    | Webcam access, image drawing, flipping        |
| `numpy`     | Coordinate math and array handling            |
| `pynput`    | Simulates keyboard key presses                |
| `python`    | Main programming language                     |

---

## 🎥 Demo Video

<video width="100%" controls>
  <source src="assets/demo_video.MP4" type="video/mp4">
  Your browser does not support the video tag.
</video>

> 🎬 File path: `assets/demo_video.MP4` (Make sure it's uploaded to the repo)

---

## 🛠️ Installation & Run
pip install -r requirements.txt

### 1. Clone the repo

```bash
git clone https://github.com/YOUR_USERNAME/Virtual-Hand-Keyboard.git
cd Virtual-Hand-Keyboard
