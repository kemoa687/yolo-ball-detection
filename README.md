# YOLO Ball Detection Project

## Overview

This project utilizes the YOLO (You Only Look Once) object detection algorithm to detect balls of various colors, specifically red, pink, green, and purple. The model has been trained to recognize and accurately identify these colored balls in images and video streams.

## Features

- **Real-time Detection**: Capable of detecting colored balls in real-time.
- **Color-Specific Detection**: Trained to detect balls of red, pink, green, and purple colors.
- **High Accuracy**: Uses the YOLOv4 model for high-precision detection.
- **Flexible Input**: Supports both image and video input for detection.

## Dependencies

- [Python 3.x](https://www.python.org/downloads/)
- [OpenCV](https://opencv.org/)
- [TensorFlow](https://www.tensorflow.org/install)
- [YOLOv4](https://github.com/AlexeyAB/darknet)

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/kemoa687/yolo-ball-detection.git
    cd yolo-ball-detection/runs
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Download YOLOv4 weights:**
    Download the YOLOv4 weights file from the [official YOLOv4 GitHub repository](https://github.com/AlexeyAB/darknet) and place it in the `model` directory.

## Usage

**Detect balls in a video:**
    ```bash
    python detect_webcam.py
    ```
