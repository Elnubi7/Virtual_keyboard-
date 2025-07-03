<div align="center">

# ✋ Virtual Hand Keyboard

Control your keyboard using only hand gestures — no physical touch needed!

<img src="https://skillicons.dev/icons?i=python,numpy,opencv,git,github" alt="tech stack" />

</div>

---

## 📌 Overview

This project simulates a **virtual keyboard** where you can type by pointing your finger in the air and making a "click" gesture with your hand.

Built using **Python**, **OpenCV**, and **cvzone**, it allows real-time hand tracking and keypress simulation using only your webcam.

---

## ⚙️ How It Works

- Uses your webcam to detect your hand in real-time.
- Tracks your index finger to detect which key you're pointing at.
- When you pinch your index and middle fingers → it triggers a key press.
- The key is typed using `pynput`, and the typed text appears on screen.
- The `<` key works as a backspace/delete.

---

## 🧠 Tech Stack & Libraries

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,numpy,opencv,git,github" alt="tech stack" />
</p>

| Library     | Purpose                             |
|-------------|-------------------------------------|
| `cvzone`    | Hand tracking (based on MediaPipe)  |
| `opencv`    | Drawing and video processing        |
| `numpy`     | Coordinate math and distances       |
| `pynput`    | Simulate keyboard input             |

---

## 🎥 Demo Video

📹 Check out the demo of me using the virtual keyboard:  
**(You can upload your video as `assets/demo_video.mp4` or paste a YouTube link below)**
