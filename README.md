Face Detection using OpenCV
Description
This Python script demonstrates real-time face detection using a webcam. It utilizes OpenCV's Haar Cascade classifier to detect faces in the video stream and draws bounding boxes around detected faces.

Features
Real-time face detection from webcam feed

Uses Haar Cascade classifier (haarcascade_frontalface_default.xml)

Displays video with detected faces outlined in blue rectangles

Adjustable frame dimensions (set to 640x360 by default)

Requirements
Python 3.x

OpenCV library (cv2)

Haar Cascade XML file (haarcascade_frontalface_default.xml) in the same directory

Installation
Install OpenCV:

bash
Copy
pip install opencv-python
Download the Haar Cascade XML file from OpenCV's GitHub repository or ensure it's in your project directory.

Usage
Run the script:

bash
Copy
python face.py
The webcam will activate, showing live video with face detection.

Press 'q' to quit the application.

Notes
The script is configured for Windows (uses CAP_DSHOW). For other operating systems, you may need to remove this parameter.

Detection parameters (scaleFactor=1.1, minNeighbors=4) can be adjusted for different detection sensitivities.
