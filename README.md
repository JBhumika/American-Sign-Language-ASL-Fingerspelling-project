# Technologies:
1. node 12.16.2
2. Tensorflow
3. Keras
4. Posenet
5. Python 3.8

# Objective
The process involves recording a video while making American Sign Language (ASL) alphabet signs, identifying the specific sign being made, and accurately displaying the corresponding alphabet class.

# Steps to run the code
- Set up the necessary software requirements (All the softwares mentioned in the technologies section)
- Execute the main.py script, which presents three choices:
1. Extract and predict alphabet videos
2. Extract and predict word videos
3. Predict alphabets and words.

# Implementation of the Project
* Create training videos for alphabets and words.
* Extract frames from each video.
* Utilize Mediapipe to generate keypoints for the extracted frames.
* Crop hand frames from each frame using wrist position as a reference point.
* Employ a segmentation algorithm to isolate alphabet frames from the word frames by utilizing the left and right arm key point coordinates.
* Merge the segmented frames to predict the corresponding alphabets and words.

