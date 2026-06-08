# Object-Detection-System-for-the-Visually-Impaired

## Overview

This project implements a real-time object detection system using the YOLO (You Only Look Once) algorithm and OpenCV. The system can detect multiple objects in images and video streams with high speed and accuracy.

## Features

* Real-time object detection
* YOLOv3-based detection model
* OpenCV integration
* Detection of multiple object classes
* Bounding box visualization
* Confidence score display

## Technologies Used

* Python
* OpenCV
* YOLOv3
* NumPy

## Project Structure

```text
Object-Detection-System/
│
├── objectdetection/
├── coco.names
├── Real-time Object Detection.py
├── requirements.txt
├── yolov3.cfg
└── README.md
```

## Installation

Install dependencies:

```bash
pip install -r requirements.txt
```

Download the YOLOv3 weights file:

```text
https://pjreddie.com/media/files/yolov3.weights
```

Place the downloaded file in the project root directory.

## Usage

Run the application:

```bash
python "Real-time Object Detection.py"
```

## Applications

* Surveillance systems
* Autonomous vehicles
* Smart traffic monitoring
* Security systems
* Computer vision research

