# OpenCV Collections

Welcome to the **OpenCV Collections** repository! This repository features various OpenCV-based projects that showcase computer vision techniques and applications. The projects are designed to be beginner-friendly and offer practical implementations using OpenCV and other helpful libraries like MediaPipe.

---

## 📂 Projects in This Collection

1. **Autonomous Drone Vision System (Simple Version)**  
   A simple, webcam-based project that simulates a drone's vision system by detecting human faces in real-time using OpenCV. This project showcases how to implement face detection and basic simulated drone movements.
   
2. **Hand Gesture Detection using OpenCV and MediaPipe**  
   A real-time hand gesture detection system using OpenCV and MediaPipe. The program detects hand landmarks to recognize basic hand gestures like open hands and fists.
   
3. **Virtual Try-On Glasses using OpenCV**  
   A webcam-based virtual try-on system that detects facial landmarks using MediaPipe and overlays a transparent glasses image onto the user's face. It simulates how glasses would look on the user's face in real-time.

---

## 🚀 Getting Started

Each project is designed to be standalone. Follow the instructions in their respective sections to set them up and run them on your machine.

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/opencv-collections.git
```

2. **Install dependencies:**

Each project has its own set of dependencies. Use the `requirements.txt` file for each project to install the necessary libraries. Navigate to the project directory and install using:

```bash
pip install -r requirements.txt
```

Alternatively, install the required libraries manually:

```bash
pip install opencv-python mediapipe numpy
```

---

## 📁 Project Structure

The repository is structured as follows:

```
opencv-collections/
├── autonomous-drone-vision/          # Autonomous Drone Vision System project
│   ├── main.py
│   ├── requirements.txt
│   └── README.md
├── hand-gesture-detection/          # Hand Gesture Detection project
│   ├── hand_gesture_detection.py
│   ├── requirements.txt
│   └── README.md
├── virtual-try-on-glasses/          # Virtual Try-On Glasses project
│   ├── virtual_try_on_glasses.py
│   ├── requirements.txt
│   └── README.md
└── README.md                        # Main repository README
```

---

## 🧠 How It Works

- **Autonomous Drone Vision System:**  
  Uses OpenCV to detect human faces from the webcam feed. The project simulates a drone's behavior based on face detection (hovering or moving toward detected faces).

- **Hand Gesture Detection:**  
  Uses MediaPipe to track hand landmarks and OpenCV to detect simple gestures like open hands and fists, displaying the results on the webcam feed in real-time.

- **Virtual Try-On Glasses:**  
  Detects facial landmarks using MediaPipe and overlays a transparent glasses image over the eyes to simulate how the glasses would look on the user’s face.

---

## 🔮 Future Improvements

Each project has potential for further development. Some ideas include:

- Adding more advanced gesture recognition.
- Incorporating multi-hand or multi-face detection.
- Implementing obstacle avoidance for the drone vision system.
- Allowing users to try on different glasses styles in the virtual try-on project.

---

## 📜 License

This repository is open-source and free to use for educational and non-commercial purposes.

---

## 📬 Contact

Feel free to reach out if you have questions, suggestions, or want to contribute. You can contact me at:  
**[Your Email or GitHub Profile Link]**

