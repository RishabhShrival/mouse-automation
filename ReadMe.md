# Hand Gesture Controlled Mouse

This project enables control of the mouse using hand gestures captured through a camera. The mouse will move according to the index finger tip, and clicking is done by tapping the thumb with the bottom of the index finger.

## Features
- Move mouse cursor with the index finger tip.
- Click by tapping the thumb with the bottom of the index finger.
- Two click modes: 
  - **Distance**: Clicks based on the distance between the thumb and the bottom of the index finger.
  - **Velocity**: Clicks based on the tap velocity and distance.
- Single hand detection to avoid confusion with multiple hands.

## Installation

Make sure to install all required libraries before running the project.

```sh
pip install opencv-python mediapipe pyautogui
