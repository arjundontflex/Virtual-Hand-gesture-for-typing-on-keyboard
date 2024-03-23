This Python script creates a virtual keyboard that can be controlled using hand gestures captured from a camera feed. It utilizes the MediaPipe library for hand tracking and OpenCV for image processing. The virtual keyboard allows users to type by hovering over keys with their index finger and performing specific gestures.

Features
Hand Gesture Recognition: The script tracks the user's hand movements in real-time using the MediaPipe Hands module.
Virtual Keyboard: The keyboard layout consists of alphanumeric keys, special keys like Caps Lock, Space, Backspace, and a clear button.
Caps Lock Functionality: Users can toggle Caps Lock on and off by hovering over the respective key.
Space and Backspace Functionality: Spacebar functionality is included to insert spaces, and backspace functionality is provided to delete characters.
Windows Key Functionality: The script can simulate pressing the Windows key to open the Start menu.
Dynamic Visual Feedback: Keys change color to indicate when they are pressed.
Dependencies
Python 3.x
OpenCV (cv2)
Mediapipe
Numpy
PyAutoGUI
