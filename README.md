# Emotion Detection using CNN and Haar Cascade

## Overview
This project involves creating an emotion detection system using a Convolutional Neural Network (CNN) model. The system detects faces in real-time using the haarcascade_frontalface_default.xml file and classifies the detected faces into various emotion categories such as happy, sad, angry, etc.

## Project Structure
1. haarcascade_frontalface_default.xml: Pre-trained Haar Cascade classifier for face detection.
2. emotion-classification-cnn-using-keras.ipynb: Script to define and train the CNN model.
3. model.h5: Pre-trained CNN model for emotion detection.
4. main.py: Script to detect emotions in real-time using the webcam.
5. README.md: Project documentation.

## Prerequisites
Ensure you have the following installed:
Python 3.x
OpenCV
TensorFlow
Keras
NumPy

## Real-Time Emotion Detection
1. Load the Haar Cascade Classifier: Use the haarcascade_frontalface_default.xml file to detect faces in images or video streams.
2. Load the Pre-trained Model: Load the model.h5 file.
3. Capture Video: Use OpenCV to capture video from the webcam.
4. Detect Faces: Apply the Haar Cascade classifier to detect faces in each frame.
5. Predict Emotion: Preprocess the detected face and pass it through the CNN model to predict the emotion.
6. Display Results: Overlay the emotion label on the video feed.

Run the real-time emotion detection script in terminal 
###### python main.py

