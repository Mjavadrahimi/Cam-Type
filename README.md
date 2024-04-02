# Cam-Type
A webcam/video-based interface for converting video to text, utilizing your index finger as a virtual pen to write words letter by letter.

this project uses 2 pre_trained models:

1- Character-Recognizer (neural network) [https://github.com/Mjavadrahimi/Character-Recognizer]

use 28*28 image as input, last layer has 26 cells(A-Z indicator)

2- Hand-Gesture-Recognizer (neural network) [https://github.com/Mjavadrahimi/Custom_Hand_Gesture]

This module interprets hand gestures, your index finger is the tip of the virtual pen.

defined hand-gestures/commands:
- index-finger-up: Indicates that the virtual pen is down, and you are typing.
- clenched-fist(Hold for 0.5 seconds): Signifies that you have finished writing a letter and are ready for the next letter.
- open-palm(Hold for 2 seconds): Deletes the last character entered.
