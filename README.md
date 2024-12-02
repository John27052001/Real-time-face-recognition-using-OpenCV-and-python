                                                                Real Time Face-Recognition using OpenCV & Python
Objective:
To develop a real-time face recognition system using OpenCV and Python that can detect and recognize faces from a live video feed.
Face detection is one of the most widely used computer vision applications and a fundamental problem in computer vision and pattern recognition.
OpenCV is a library which is used to carry out the image processing using programming languages (Python). This project utilizes OpenCV using webcam.

Software requirements:
Python 3.13.0
OpenCV
NumPy

System Components:
 Face Detection: Uses a Haar Cascade model to detect faces in each video frame
 Face Recognition: Recognizes detected faces by comparing them with a database of known faces using the LBPH (Local Binary Patterns Histograms) face recognizer.

Methodology:
 Dataset Preparation: Collect and label images of individuals for training the recognizer
 Training the Model: Train the LBPHFaceRecognizer on the dataset, mapping each person to a unique ID
 Real-Time Video Processing:
Capture frames from the webcam
Convert each frame to grayscale for efficient processing
Detect faces in the frame and recognize them by comparing with trained IDs
Display recognized names and confidence scores on the screen.
