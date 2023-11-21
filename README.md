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
   git clone https://github.com/Devansh-Gupta-Offical/Pose-Estimation.git
   cd hand_angle_estimation
   ```
2. Install the required dependencies:
   ```
   pip install mediapipe opencv-python
   ```

## **Usage**
Run the hand_tracking.py script to start hand tracking using your webcam:
```
python hand_angle_estimation.py
```

## **Explanation**
The Python script (hand_angle_estimation.py) performs the following:
- Initializes hand tracking using MediaPipe and OpenCV.
- Defines a list of finger joint indices for angle calculation.
- Contains functions to calculate finger angles and retrieve hand labels.
- Captures video frames from the webcam and processes them in real-time.
- Visualizes hand landmarks and connections.
- Displays left/right hand labels and calculates angles between finger joints.

### **Code Structure**
- hand_angle_estimation.py: Main Python script for real-time hand tracking.
- Output Images/: Directory to store captured images (commented out in the script).

## **Results**
![image](https://github.com/Devansh-Gupta-Official/Pose-Estimation/assets/100591612/ea5053db-cc7f-4378-ba8a-358ad90ffead)




hand_face_estimation.py
# **Real-time Holistic Tracking using MediaPipe and OpenCV**
This project demonstrates real-time holistic tracking using MediaPipe and OpenCV. It utilizes the Holistic model from MediaPipe to detect and visualize face landmarks, hand gestures, and body poses from a live webcam feed.

## **Overview**
The script holistic_tracking.py performs the following tasks:
- Captures live video from the webcam using OpenCV (cv2.VideoCapture).
- Initializes the holistic model from MediaPipe (mp_holistic.Holistic).
- Processes each frame to detect facial landmarks, hand gestures (left and right), and body poses.
- Visualizes the detected landmarks and connections in real-time using OpenCV and MediaPipe drawing utilities.

## **Dependencies**
- Python 3.x
- `mediapipe`
- `opencv-python`

## **Installation**
1. Clone this repository:
   ```
   git clone https://github.com/Devansh-Gupta-Official/Pose-Estimation.git
   cd hand_face_estimation
   ```
2. Install the required dependencies:
   ```
   pip install mediapipe opencv-python
   ```

## **Usage**
Run the holistic_tracking.py script to start hand tracking using your webcam:
```
python hand_face_estimation.py
```

## **Results**
The script visualizes the following in the webcam feed:
- Face Landmarks: Displayed with unique colors and contours.
- Right Hand Gestures: Marked with connections and circles for each landmark.
- Left Hand Gestures: Similar visualization as the right hand.
- Body Poses: Detected and displayed with connecting lines.

![image](https://github.com/Devansh-Gupta-Official/Pose-Estimation/assets/100591612/0d75afda-0b3c-479c-aaf7-7a7a6c0b3117)







  

  
