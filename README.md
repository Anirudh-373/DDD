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
