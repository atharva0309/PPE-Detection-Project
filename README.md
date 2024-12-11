# PPE Detection Project

This project is a workplace safety PPE detection system that identifies whether individuals are wearing necessary Personal Protective Equipment (PPE) such as helmets, vests, goggles, and gloves. The model uses the YOLO (You Only Look Once) object detection algorithm and is deployed using a pre-trained model from Ultralitycs' platform for detecting PPE items in images and videos.

## Project Structure

The project includes the following files:
- **ppe_detection_video.py**: Detects PPE in video files and prints missing PPE statements.
- **ppe_detection_image.py**: Detects PPE in a single image and prints missing PPE statements.
- **requirements.txt**: List of required Python libraries to run the project.
- **README.md**: This file.

## Features

- **PPE Detection from Video**: Detects PPE in real-time from video files and generates missing PPE alerts for each frame.
- **PPE Detection from Images**: Processes single images, detecting the presence of PPE and printing alerts for missing items.
  

## Requirements

Before running the project, ensure you have the required dependencies installed:

- Python 3.x
- OpenCV
- ultralytics
- supervision
- torch

You can install the dependencies by running:

```bash
pip install -r requirements.txt
