# skeleton-tracing
Real-time human pose detection using MediaPipe and OpenCV.
This is usually used for virtual try on models .

## Libraries Used
- Python 3.9
- MediaPipe 0.10.11
- OpenCV 4.13.0
- NumPy 1.24.3

## Setup
pip install mediapipe==0.10.11
pip install opencv-python
pip install numpy==1.24.3

## Run
python skeleton_tracing.py

## Controls
(key shortcuts)
- Q → Quit
- S → Save snapshot
  <img width="1920" height="1080" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/b506dff4-c996-43e3-bf6a-f5242f79b362" />
<img width="1920" height="1080" alt="Screenshot (29)" src="https://github.com/user-attachments/assets/9d5b2aa7-f1f0-4d07-809f-501aebd797bb" />

## Features
- Real-time skeleton tracing
- 33 body landmarks detected
- Body measurements (shoulder, height, hip, weight)
- Here we were able to see the 33 landmarks along with joining of landmarks (skeleton image of our body structure)
