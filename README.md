## Face Detection using OpenCV and Python
## Description
This project demonstrates a simple face detection application using OpenCV and Python. It utilizes OpenCV’s pre-trained Haar Cascade classifier to detect faces in images or real-time video streams. Face detection is a fundamental task in computer vision, used in applications like security systems, user authentication, and interactive user interfaces.

## Features
Detects faces in images and live webcam feed
Draws rectangles around detected faces
Uses OpenCV’s efficient Haar Cascade classifier

## Requirements
Python 3.x
OpenCV (opencv-python)

## Installation
Clone the repository:
git clone https://github.com/Abhishek180-Kumare/face-detection-opencv.git
cd face-detection-opencv

## Install dependencies:
pip install opencv-python

## Usage
Detect faces in an image
python detect_faces_image.py --image path_to_image.jpg

## Detect faces in webcam video
python detect_faces_webcam.py

## How it works
The program loads a pre-trained Haar Cascade model for face detection.
The input image or video frame is converted to grayscale.
The detector scans the image to find faces and returns their coordinates.
Detected faces are highlighted with rectangles.

## Example
License
This project is licensed under the MIT License
