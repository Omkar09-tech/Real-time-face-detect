Real-Time Face Detector

A lightweight computer vision project that detects human faces in real time using a webcam and Python + OpenCV.

📌 Overview

Real-Time Face Detector captures live video from your webcam and uses OpenCV’s pre-trained Haar Cascade Classifier to detect faces in each frame. Detected faces are highlighted with bounding boxes in real time.

✨ Features

* Real-time face detection
* Webcam video capture
* Multiple face detection
* Bounding boxes around detected faces
* Lightweight and beginner-friendly
* Built with OpenCV

🛠️ Tech Stack

* Language: Python
* Library: OpenCV
* Detection Model: Haar Cascade Classifier
* Input: Webcam

📂 Project Structure

real-time-face-detector/
│
├── main.py
├── haarcascade_frontalface_default.xml
├── requirements.txt
└── README.md

⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/real-time-face-detector.git
cd real-time-face-detector

Install the required dependency:

pip install -r requirements.txt

Or install OpenCV directly:

pip install opencv-python

▶️ Usage

Run the application:

python main.py

Allow the application to access your webcam. The program will display the live camera feed and highlight detected faces.

Press Q to exit.

🧠 How It Works

Webcam
   ↓
Capture Video Frame
   ↓
Convert to Grayscale
   ↓
Haar Cascade Face Detection
   ↓
Detect Faces
   ↓
Draw Bounding Boxes
   ↓
Display Live Result

🚀 Future Improvements

* Face recognition with user identification
* Real-time attendance system
* Face tracking
* Mask detection
* Deep-learning-based face detection
* Detection confidence scores
* GUI interface

📄 License

This project is intended for educational and personal use.

⸻

⭐ If you found this project useful, consider giving the repository a star.
