# Hand Gesture Mouse Control

> Controlling a computer mouse using just a hand — no mouse needed!

##  What is this project?

This is an AI-powered project where a webcam detects hand movements in real-time and moves the mouse cursor on the screen. Just raise your index finger in front of the camera — and the cursor follows!

## The Struggle Behind This Project

This was not easy! Here are the real challenges I faced:

- ❌ `mediapipe` version was wrong → had to downgrade to `0.10.9`
- ❌ `opencv` DLL error → switched versions multiple times
- ❌ `numpy` conflict → downgraded to `1.24.3`
- ❌ Terminal kept freezing → restarted VS Code multiple times
- ✅ After all this... **it finally worked!** 🎉

## 🛠️ Tools & Technologies

| Tool | Why I used it |
|------|--------------|
| Python | Main programming language |
| OpenCV | Opens webcam and shows video |
| MediaPipe | Detects hand and finger position |
| PyAutoGUI | Moves the mouse on screen |

## How to Run ?

pip install opencv-python mediapipe pyautogui

python gesture.py

Then show your index finger to the webcam — the cursor will follow! 🖐️

##  About Me

- 🎓 CSE Final Year Student, Daffodil International University
- 🔬 Published Researcher — IDAA 2025 (Taylor & Francis)
- 🎯 Goal: Full scholarship for higher studies abroad

## 📸 Demo

![Demo](demo.png)
