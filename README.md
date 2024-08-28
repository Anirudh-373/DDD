**Driver Drowsiness Detection System**

This project implements a real-time drowsiness detection system using Python, OpenCV, dlib, and Pygame. 
The system monitors a user's eye aspect ratio (EAR) to detect if they are drowsy or blinking excessively. 
If the user's eyes are closed for a certain period, an alarm is triggered to alert them.

Features:
 - Real-Time Eye Detection: Uses a webcam to capture video and detect eyes in real-time.
 - Eye Aspect Ratio Calculation: Computes the eye aspect ratio to determine if the eyes are closed.
 - Drowsiness Detection: Triggers an alarm if eyes remain closed beyond a predefined threshold.
 - Sound Alert: Plays an alarm sound when drowsiness is detected.

Requirements:
 - Python 3.x
 - OpenCV
 - dlib
 - imutils
 - scipy
 - numpy
 - pygame

I have used a pretrained model from the dlib library which is used for facial landmark detection.
Download it from here: https://huggingface.co/public-data/dlib_face_landmark_model/blob/main/shape_predictor_68_face_landmarks.dat

How to run this project:
 - Create a virtual environment (conda recommended) with any of these Python versions: 3.7 - 3.12 (I have used version 3.8), activate the environment.
 - Install the libraries using this command: pip install opencv-python imutils scipy numpy pygame cmake
 - Download and Install Cmake from this website: https://cmake.org/download/
 - To install dlib library, Download the folder from this repository: https://github.com/z-mahmud22/Dlib_Windows_Python3.x. After Downloading, extract just the .whl file which is corresponding to your   Python version. To find it check the cp3xx-cp3xx version in the file name. Since I have used Python 3.8, my corresponding dlib version is: cp38-cp38
 - Save the .whl file in the project directory.
 - Open the terminal in project directory and type: python -m pip install _yourfilenameofdlib.whl_ file (This is the manual installation of dlib library)
 - Once all the libraries are installed, type "python _yourfilename.py_", the camera will open up.
 - To close the camera, press Ctrl+C in the terminal.
