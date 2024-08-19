# cv2-objectTracker

# Overview
The Object Tracker is a Python project that uses the Lucas-Kanade method for optical flow to track objects in a video. The program identifies key features in the initial frame, then tracks the motion of these features throughout the video. It calculates the velocity and direction of each tracked feature and overlays this information on the video.

# Features
- Optical Flow Calculation: Uses the Lucas-Kanade method to compute the optical flow between frames.
- Object Tracking: Identifies and tracks key features (corners) across video frames.
- Velocity and Direction: Calculates and displays the velocity and direction of tracked objects.
- Video Output: Generates a video with the tracked features, their paths, and their velocities and directions displayed.

# Requirements
- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- FFmpeg (for video conversion)
