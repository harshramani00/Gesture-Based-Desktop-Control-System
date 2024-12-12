# Gesture-Based-Desktop-Control-System
## Overview
The Gesture-Based Desktop Control System is a project designed to provide a touchless and intuitive way to control desktop computers using hand gestures. The system leverages computer vision and machine learning techniques to detect and interpret hand gestures, translating them into basic mouse functionalities such as cursor movement, clicks, and drag operations.

## Features
- Cursor control using hand gestures.
- Simulated left and right mouse clicks.
- Drag-and-drop functionality.
- Scrolling operations based on gesture movements.
- Real-time gesture detection using a standard webcam.


## Technologies Used
- Python 3.8: Core programming language.
- OpenCV: For video capture and image processing.
- MediaPipe: For hand tracking and gesture recognition.
- PyAutoGUI: To simulate mouse actions.
- NumPy: For numerical computations and array manipulations.


## Installation


### Prerequisites
Python 3.8 installed on your system.
A webcam or built-in camera.


### Steps to Create Environment and Install Dependencies
- Clone the Repository:
```shell
git clone https://github.com/yourusername/gesture-desktop-control.git
```
```shell
cd gesture-desktop-control
```
- Create conda Environment
```shell
conda create --name gesture_env python=3.8 -y  
```
- Activate the Conda Environment:
```shell
conda activate gesture_env  
```
- Install the Required Dependencies:
```shell
pip install -r requirements.txt  
```


## Usage :
- Ensure Your Webcam is Connected and Working.
- Run the Main Script:
```shell
python main.py
```
- Follow the On-Screen Instructions:
- Use specific hand gestures for cursor movement, clicking, and scrolling.


## How It Works
- The system captures video frames from the webcam.
- MediaPipe is used to detect and track the user's hand landmarks.
- Based on the landmarks, specific gestures (like pinching or finger positions) are mapped to mouse actions.
- PyAutoGUI simulates these actions on the desktop.


## Future Enhancements
- Support for multi-hand gestures (e.g., pinch-to-zoom).
- Improved gesture recognition in low-light or complex environments.
- Integration with gaming and VR systems.
- Additional customizable gestures.


## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

## Steps to Contribute
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Commit your changes with descriptive messages.
- Submit a pull request.





