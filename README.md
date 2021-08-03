# drowsiness

This project is a computer vision system that can automatically detect driver drowsiness in a real-time video stream and then play an alarm and screen alert if the driver appears to be drowsy.

Applications


This code can detect your eyes and alert when the user is drowsy with an alarm sound and screen alert.

 

Requirements for the project


1)The code is in Python 3.9.1([version 2.7]or higher will work).
2)shape_predictor_68_face_landmarks.dat file(must be included in the same directory as that of the .py file) 

 


# Dependencies


1) import cv2
2) import imutils
3) import dlib
4) import scipy
5) from playsound import playsound

 

# Description


This could be used by riders who tend to drive for a longer period of time that may lead to accidents. The code can be integrated in a real-time video stream in the car/vehicle. When drowsy, an alarm sound and a screen alert would play to awaken the driver.

 

# Condition


The code checks 20 consecutive frames and if the Eye Aspect ratio is less than 0.25, Alert is generated.

 


# Execution


1)To run the code from cmd, type "python Drowsiness_Detection.py" after including the necessary .dat file and alarm music.
2)The code can run on any python IDE like Visual Studio Code.

 
