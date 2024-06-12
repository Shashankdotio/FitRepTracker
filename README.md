# FitRep Tracker: Real-Time Bicep Curl Counter
This project leverages computer vision techniques to estimate human poses and count repetitions of bicep curls in real-time. 
Using Mediapipe, a powerful machine learning framework developed by Google, the system accurately identifies and tracks key body landmarks. OpenCV, an open-source computer vision library, processes video input to detect these landmarks and visualize the results.

The project focuses on recognizing the specific motion involved in performing bicep curls. By analyzing the positions and movements of key landmarks such as the shoulders, elbows, and wrists, the system can determine when a full bicep curl is completed. It counts the repetitions and provides real-time feedback, making it an effective tool for fitness enthusiasts to monitor and improve their workout routines.

## How to run:
install the necessary dependencies:
>pip install mediapipe opencv-python

import the dependencies:
>import cv2

>import mediapipe as mp

>import numpy as np

>mp_drawing = mp.solutions.drawing_utils

>mp_pose = mp.solutions.pose

Extract and run main.py in your IDE
