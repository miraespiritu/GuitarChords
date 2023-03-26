# GuitarPicks
RowdyHacks 2023 Project

This project uses the MediaPipe Gesture Recognizer Task found here:
https://developers.google.com/mediapipe/solutions/vision/gesture_recognizer

We were able to follow a tutorial given by Ivan Goncharov that helped us understand how to add our own gestures, found here:
https://youtu.be/a99p_fAr6e4

The Github repo that includes the model and keypoints classifications we used is found here:
https://github.com/kinivi/hand-gesture-recognition-mediapipe

To run the program, just run the app.py

When adding new gestures to the dataset, press 'K' while the video feed is open. Then use 0-9 to add keypoints to the appropriate label.
Open -- 0
Close -- 1
Pointer -- 2
OK -- 3
Peace -- 4
A chord -- 5
C chord -- 6
E chord -- 7
D chord -- 8
G Chord -- 9

The keypoints get added to the keypoint.csv under the label number.

Then rerun the keypoint_classification jupyter notebook so the data is trained with the new keypoints from the keypoint.csv.

Run app.py again