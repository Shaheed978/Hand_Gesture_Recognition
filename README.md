# Hand_Gesture_Recognition
Hand Gesture Recognition

In this project, I developed a Hand Gesture Recognition and Image Capture System using Python and OpenCV. The system detects hand gestures in real-time from a live video feed using a webcam. I used the cvzone.HandTrackingModule to track hand landmarks and compute the bounding box around the detected hand.

Once the hand is detected, the system crops the hand region from the image and resizes it to fit a fixed 300x300 pixel canvas for consistent processing. The aspect ratio of the hand is maintained to ensure proper scaling. If the gesture has a higher aspect ratio (height greater than width), the width is scaled to fit; otherwise, the height is scaled. The cropped and resized hand image is displayed alongside the original image.

Additionally, when the user presses the "s" key, the system saves the captured hand image into a designated folder with a timestamp as part of the file name. This functionality allows for easy data collection of hand gesture images, useful for further analysis, training gesture recognition models, or building interactive systems.

Key technologies used: Python, OpenCV, cvzone, NumPy.
