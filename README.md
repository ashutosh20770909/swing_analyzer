# SmartSwing: AI-Powered Golf Swing Analyzer

## Project Overview
SmartSwing is a computer-vision based application that democratizes professional swing analysis. It uses **MediaPipe Pose Estimation** to detect a golfer's biomechanics in real-time and provides actionable feedback.

## Key Features
* **Swing Detection:** Auto-segments video into address, backswing, and follow-through.
* **Biomechanical Analysis:** Tracks shoulder-to-hip separation and spine angle.
* **Visual Feedback:** Overlays the ideal swing plane on the user's video.

## Tech Stack
* Python 3.8+
* OpenCV (`cv2`)
* MediaPipe (`mediapipe`)
* NumPy

## How to Run
1. Install dependencies: `pip install opencv-python mediapipe numpy`
2. Run the script: `python swing_analyzer.py`
