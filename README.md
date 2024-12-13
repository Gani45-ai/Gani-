This project uses computer vision techniques to track the movement of a green object through a webcam and simulates a keyboard action (pressing the "space" bar) when the object moves upwards.

Project Description:

1. Color Detection: The program detects a green object by filtering the camera feed using a specific range of green colors in the HSV color space.


2. Object Tracking: The contours of the green object are found, and if the object moves upwards (y-coordinate decreases), the program simulates pressing the "space" key using the pyautogui library.


3. Real-time Action: The webcam feed is processed in real-time, drawing bounding boxes around the detected object and triggering actions based on its movement.



Key Libraries:

OpenCV (cv2): Used for computer vision tasks like reading the webcam feed, detecting colors, and finding contours.

NumPy (np): Used for handling arrays, specifically to define the color range for green.

PyAutoGUI: Simulates pressing the "space" key based on the object's movement.


Purpose:

This project can be used for hands-free control applications where a specific movement of an object (like a hand or a green object) triggers an action, such as space bar presses.
