Face and Eye Detection Model using OpenCV
=========================================

Overview:
---------
This project implements a real-time Face and Eye Detection system using OpenCV and Haar Cascade Classifiers.
It can detect human faces and eyes in a webcam feed or an image using pre-trained models.

Features:
---------
- Real-time face and eye detection from webcam or images
- Uses Haar Cascade classifiers (lightweight and fast)
- Simple, easy-to-understand implementation
- No need for deep learning or heavy frameworks

Technologies Used:
------------------
- Python
- OpenCV
- Haar Cascade XML files

How It Works:
-------------
1. The system captures video from the webcam (or reads an image).
2. It loads a pre-trained Haar Cascade classifier to detect faces.
3. Once a face is detected, a second Haar classifier detects eyes inside the face region.
4. Rectangles are drawn around the detected faces and eyes.

File Structure:
---------------
face-eye-detection/
│
├── haarcascade_frontalface_default.xml
├── haarcascade_eye.xml
├── face_eye_detection.py
├── README.txt
└── sample_image.jpg

How to Run:
-----------
1. Make sure Python and OpenCV are installed:
   pip install opencv-python

2. Run the program:
   python face_eye_detection.py

Applications:
-------------
- Face recognition preprocessing
- Eye tracking
- Attendance systems
- Real-time monitoring
- Human-computer interaction

