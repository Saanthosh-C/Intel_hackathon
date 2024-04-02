# Multimodal Emotion Recognition in Sign Language

## Problem Statement:

The challenge addressed in this project is to design and implement a system capable of recognizing emotions conveyed through sign language using multiple modalities, such as hand gestures, facial expressions, and body movements. The objective is to improve communication accessibility for individuals with hearing impairments by accurately interpreting the emotional content conveyed in sign language interactions. This project aims to leverage technology to bridge communication gaps and promote inclusivity and empathy in interactions involving sign language.

## Solution:

The solution employs the following steps:

Data Collection: The system captures video frames and processes them using the MediaPipe library to detect facial landmarks, body poses, and hand gestures. These landmarks are then used as input features for emotion recognition.

Feature Extraction: Key points representing facial landmarks, body poses, and hand gestures are extracted from the video frames using the MediaPipe library.

Model Training: The extracted features are fed into a deep learning model, specifically an LSTM (Long Short-Term Memory) neural network, for training. This model learns to classify the emotions conveyed through sign language based on the extracted features.

Model Evaluation: The trained model is evaluated using a separate test dataset to assess its accuracy in recognizing emotions expressed through sign language.

Real-time Emotion Recognition: The trained model is deployed to perform real-time emotion recognition on live video feeds. The system continuously processes the video frames, predicts the emotions conveyed through sign language, and displays the recognized emotions on the screen.

## Requirements:

Python 3.x

OpenCV

NumPy

Matplotlib

MediaPipe

TensorFlow

scikit-learn

oneDAL (Intel oneAPI Data Analytics Library)

oneDNN (Intel oneAPI Deep Neural Network Library)

## Instructions for Execution:

Install the required libraries mentioned in the Requirements section.
Ensure that the webcam or video input device is connected properly.
Run the provided Python script (emotion_recognition_sign_language.py).
The script will start capturing video frames from the webcam and display the real-time emotion recognition results on the screen.

## Note:

This project utilizes Intel oneAPI libraries, specifically oneDAL and oneDNN, for optimized performance and efficient data processing. Ensure that these libraries are properly installed and configured for the best results.

## References:

MediaPipe: https://google.github.io/mediapipe/

TensorFlow: https://www.tensorflow.org/

Intel oneAPI: https://www.intel.com/content/www/us/en/developer/tools/oneapi.html
