# Drone_Autonomous

## Overview
This project develops an autonomous drone system capable of performing navigation, tracking, and gesture recognition tasks. It integrates computer vision algorithms, real-time path planning, and control modules to enable responsive flight operations.

## Features
- **Autonomous Navigation:** Plan and follow paths in dynamic environments.
- **Human Tracking:** Detect and follow a specific target using vision-based tracking.
- **Gesture Recognition:** Recognize predefined hand gestures to command drone actions such as follow, hover, or retreat.
- **Real-Time Control:** Integrate perception and control loops for robust drone autonomy.

## Requirements
- Python 3.x
- OpenCV
- PyTorch / TensorFlow (depending on your CV model)
- ROS (optional, if using for real-time communication)
- Drone SDK (e.g., Tello SDK)

## Installation
Clone this repository and install dependencies:
```bash
git clone https://github.com/YourUsername/Drone_Autonomous.git
cd Drone_Autonomous
pip install -r requirements.txt
