# advanced_python_projects
1: Live Face Detection Using OpenCV
This project implements a real-time face detection system using OpenCV's Haar Cascade Classifier. The application captures live video feed from the webcam, detects faces, and highlights them with bounding boxes.

Features
Uses Haar Cascade Classifier for accurate face detection.
Detects faces in real-time from live webcam feed.
Highlights detected faces with blue bounding boxes.
Easy-to-use interface with an option to quit using the 'q' key.

How It Works
Captures video from the default webcam.
Converts frames to grayscale for efficient processing.
Detects faces using the haarcascade_frontalface_default.xml pre-trained model.
Draws bounding boxes around detected faces on the live video feed.

Technologies Used
Python: Programming language for the application.
OpenCV: Library for computer vision tasks.

Instructions to Run
Clone the repository:
git clone <repository_url>
Install dependencies:
pip install opencv-python
Run the script:
python live_face_detection.py

Requirements
Python 3.x
OpenCV library (opencv-python)

Usage
Launch the script to start face detection.
Press 'q' to exit the application.
