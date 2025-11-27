# Object-detection-using-web-camera---workshop

## AIM
This project demonstrates real-time object detection using the YOLOv4 model with OpenCV and a web camera. The system detects multiple objects in live video streams and displays bounding boxes, class labels, and confidence scores.

## Features

Real-time detection through webcam

Pretrained YOLOv4 on COCO dataset (80 classes)

Bounding boxes with class labels & confidence values

Non-Maximum Suppression (NMS) to remove duplicate boxes

Easy to set up and run

## Requirements

Python 3.7+

OpenCV

NumPy

Install dependencies:

pip install opencv-python numpy

## Setup Instructions

Clone or download this repository.

Download the following YOLOv4 files:

yolov4.weights

yolov4.cfg

coco.names

Place them in the project folder.

Run the script:

python object_detection.py

## How It Works

The webcam feed will open.

Detected objects will be shown with green bounding boxes and labels.

Press q to exit the window.
