# Pose-Estimation

hand_angle_estimation.py
# **Real-time Hand Tracking with MediaPipe and OpenCV**
This project showcases real-time hand tracking using MediaPipe and OpenCV. It detects hand landmarks, calculates angles between finger joints, and visualizes the results in a live video stream.

## **Dependencies**
- Python 3.x
- `mediapipe`
- `opencv-python`

## **Installation**
1. Clone this repository:
   ```
   git clone https://github.com/yourusername/hand-tracking.git
   cd hand-tracking
   ```
2. Install the required dependencies:
   ```
   pip install mediapipe opencv-python
   ```

## **Usage**
Run the hand_tracking.py script to start hand tracking using your webcam:
```
python hand_tracking.py
```

## **Explanation**
The Python script (hand_tracking.py) performs the following:
- Initializes hand tracking using MediaPipe and OpenCV.
- Defines a list of finger joint indices for angle calculation.
- Contains functions to calculate finger angles and retrieve hand labels.
- Captures video frames from the webcam and processes them in real-time.
- Visualizes hand landmarks and connections.
- Displays left/right hand labels and calculates angles between finger joints.

### **Code Structure**
- hand_tracking.py: Main Python script for real-time hand tracking.
- Output Images/: Directory to store captured images (commented out in the script).

## **Results**
![image](https://github.com/Devansh-Gupta-Official/Pose-Estimation/assets/100591612/ea5053db-cc7f-4378-ba8a-358ad90ffead)


  
