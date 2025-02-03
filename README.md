# Face-Recognition-Using-OpenCv

![Uploading Screenshot 2025-02-03 142808.png…]()


This project demonstrates real-time face detection using a webcam feed and OpenCV. The script utilizes a pre-trained Haar Cascade Classifier to detect faces and display them with bounding boxes in a live video feed.

#Requirements
To run this project, you'll need:

Python 3.x
OpenCV library (opencv-python)
To install OpenCV, use the following pip command:
> pip install opencv-python
Setup
Install Dependencies:
Install the required Python libraries by running:
> pip install opencv-python
Face Detection Model:
The project uses a pre-trained Haar Cascade model to detect faces. Ensure you have the model file, which is typically located at:

> C:/Users/thouf/AppData/Roaming/Python/Python312/site-packages/cv2/data/haarcascade_frontalface_default.xml
If the path differs on your system, download the file from the OpenCV GitHub and update the path accordingly in the script.

#How to Run
Save the Script:
Save the Python script in a file (e.g., face_detection.py).

Execute the Script:
Open a terminal or command prompt, navigate to the directory where the script is saved, and run the script using:

> python face_detection.py
Stop the Video:
Press the spacebar to stop the video feed and close the window.

#How It Works
Haar Cascade Classifier:
The script loads a pre-trained Haar Cascade model for face detection, which scans each frame of the video for faces.

#Real-Time Face Detection:
The webcam feed is captured, and each frame is converted to grayscale for face detection. The detected faces are outlined with green rectangles.

#Exit the Program:
To exit the video feed, press the spacebar. This stops the webcam capture and closes the application.

Notes
Ensure the Haar Cascade model file (haarcascade_frontalface_default.xml) is in the correct path.
The default camera (ID 0) is used for video capture. If you have multiple cameras, you can modify the cv2.VideoCapture() parameter to select a different one.


