---

# Hand Gesture Brightness Controller

## Overview

This Python script utilizes computer vision to control screen brightness based on hand gestures. The code uses the `mediapipe` library to detect hand landmarks, calculates the distance between two specified landmarks, and adjusts screen brightness accordingly.

## Prerequisites

- Python 3.x
- OpenCV
- Mediapipe
- NumPy
- Screen Brightness Control (`screen_brightness_control`)

## Setup

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the script:

   ```bash
   python gesture_brightness_controller.py
   ```

   The script will use your webcam to capture hand gestures in real-time. To exit the program, press 'q'.

## How it Works

The script detects hand landmarks, calculates the distance between two specified points, and maps that distance to adjust screen brightness. Longer distances result in higher brightness levels.

## Customization

Feel free to modify the code to suit your needs. You can change the specified landmarks, adjust brightness range, or incorporate additional gestures.

