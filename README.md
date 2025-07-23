# Real-Time Face and Eye Detection Using OpenCV and Python
## Overview

This project demonstrates a **real-time face and eye detection** system using Python and OpenCV. It utilizes Haar Cascade classifiers to detect faces and eyes from a live webcam feed, drawing bounding boxes and labels around detected features.

---

## Features

- Real-time detection of faces and eyes from webcam video.
- Uses Haar Cascade classifiers for robust detection.
- Visual feedback with labeled bounding boxes for faces and eyes.
- Simple interface: Press **'w'** to exit the application.

---

## Requirements

- Python 3.x
- OpenCV (`opencv-python`)
- NumPy

---

## Installation

1. **Clone or Download** this repository.
2. **Install dependencies** using pip:
   ```
   pip install opencv-python numpy
   ```
3. **Download Haar Cascade XML files** if not present:
   - [haarcascade_frontalface_default.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)
   - [haarcascade_eye.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_eye.xml)
   - Place these files in the same directory as the script.

---

## Usage

1. Run the script:
   ```
   python Face_Eye_Detection.py
   ```
2. A window will open showing the webcam feed with detected faces and eyes highlighted.
3. Press **'w'** to exit the application.

---

## How It Works

- Captures video from the default webcam.
- Converts each frame to grayscale for processing.
- Detects faces using the face Haar Cascade.
- For each detected face, detects eyes within the face region.
- Draws rectangles and labels for each detected face and eye.

---

## Project Highlights

- **Real-time computer vision** application.
- **High detection accuracy** using pre-trained Haar Cascades.
- **User-friendly interface** with immediate visual feedback.

---

## License

This project is for
