# Emotion Detection Program:

## This emotion detection program was trained using Teachable Machine to identify the following emotions: happy, normal (monotone), surprise, and if there's no one present. 

## Overview Emotion detection is crucial for individuals who are visually impaired as it supports and enhances social interactions by providing insights into the emotional states of others. This program utilizes the Jetson Nano, a powerful AI computing platform, to perform real-time emotion recognition. 

# How It Works 

## 1. **Training**: The model was trained using Teachable Machine, a tool that allows users to create custom machine learning models without requiring extensive coding knowledge. The training process involved capturing images of individuals expressing different emotions and labeling them accordingly. The model was then trained to recognize these emotions based on the visual data. 

## 2. **Integration with Jetson Nano**: The trained model is deployed on the Jetson Nano, which provides the computational power necessary for real-time emotion recognition. The Jetson Nano's GPU accelerates the processing of image data, allowing the program to analyze and classify emotions quickly. 

## 3. **Image Capture**: The program uses a camera connected to the Jetson Nano to capture live video feeds. These feeds are continuously analyzed by the emotion detection model. 

## 4. **Emotion Classification**: The captured images are processed by the model, which classifies them into one of the predefined emotion categories: happy, normal (monotone), surprise, or no one present. The classification results are used to provide feedback on the emotional state of individuals in the camera's view. 

## 5. **Output and Feedback**: Based on the detected emotion, the program can generate notifications or visual/auditory cues to assist users in understanding the emotional context of their interactions. This feedback is designed to enhance social engagement and communication for visually impaired users. 

## Usage Dirrections:

# Required for running the emotion detection model: **Camera**: A compatible camera for capturing real-time video feeds. - **Teachable Machine Model**: The trained model file needs to be loaded onto the Jetson Nano. ## Installation 1. Set up your Jetson Nano according to the official documentation. 2. Install the necessary dependencies and libraries. 3. Load the trained model file onto the Jetson Nano. 4. Connect and configure the camera. 5. Run the emotion detection program and follow the provided instructions for calibration and usage. 
