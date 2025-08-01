🚗 Head Gesture Controlled Hill Climb Racing
A real-time gesture-based control system that allows users to play Hill Climb Racing using head movements, specifically nose tracking. This project utilizes MediaPipe and OpenCV to detect facial landmarks and map specific nose gestures to keyboard inputs for game control.

🎯 Features
🧠 Real-time facial landmark detection using MediaPipe.

👃 Nose tracking to detect directional gestures.

🎮 Simulates keyboard inputs for GAS and BRAKE based on head tilt.

🤖 Enhances accessibility and user interaction in gaming.

🛠️ Built with Python, OpenCV, and MediaPipe.

🛠 Tools & Technologies
Python

OpenCV

MediaPipe

PyAutoGUI or keyboard (for keypress simulation)

🖼 How It Works
The webcam captures live video.

MediaPipe detects facial landmarks in real time.

The position of the nose tip is continuously tracked.

If the nose moves:

Right ➡️ simulate GAS (e.g., pressing "Right Arrow").

Left ⬅️ simulate BRAKE (e.g., pressing "Left Arrow").

Key presses are mapped and sent to the game window.

📁 Project Structure
bash
Copy
Edit
head-gesture-hill-climb-racing/
├── main.py              # Main script to run the detection and control
├── requirements.txt     # List of dependencies
├── README.md            # Project documentation
└── assets/              # (Optional) Screenshots or demo video
