# Drowsiness-Detection-System
Here we use openCV for gathering images from webcam and feed them into a deep learning model which will classify the person's eyes as 'open' or 'Closed'
STEPS involved:
S1: Take image as input from a camera.
S2:Detect the face in the image and create a Region of Interest (ROI).
S3:Detect the eyes from ROI and feed it to the classifier.
S4:Classifier will categorize whether eyes are open or closed.
S5:Calculate score to check whether the person is drowsy.

The model we used is built with Keras using Convolutional Neural Networks (CNN).







