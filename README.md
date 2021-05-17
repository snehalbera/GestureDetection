# Gesture Detection System

This project uses TensorFlow's Object Detection API and OpenCV on Python 3.7 to detect the user's hand gestures and outputs the detected gestures in speech. Gestures can be mapped to different actions and new gestures can be trained.

Works best on self-trained user images for detection.

Dependencies:
* Python 3.5 and above
* PyQT5
* PyTTSx3
* OpenCV
* TensorFlow 2

Features:
* New gesture training
* Detect gesture in real time, pre-recorded video and images
* Determine speech

## Algorithm

![Detection Algorithm](/Snapshots/Image 1.jpg)

The `process()` loop can be summarized as follows:
1. Capture the gestures
2. Label the gestures
3. Create XML for the gestures
4. Separate 70% for training and 30% for testing
5. Generate a model using transfer learning
6. Real time detection using a webcam and OpenCV
7. Extract the label for the detected gesture and output speech

## Installation
* [labelImg](https://github.com/tzutalin/labelImg)
* [TensorFlow](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html)

## Usage

**creategesture**:
**training**:
**photodetect**:
**videodetect**:
**real-timedetect**:
