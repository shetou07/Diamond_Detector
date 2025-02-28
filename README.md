# Diamond_Detector

## Overview

The Diamond and Skull Tracker is a computer vision project that tracks a diamond and the skull covering it in a video. It uses a combination of template matching and OpenCV’s CSRT tracker to detect and track these objects. This project is designed to run in Google Colab, allowing for easy experimentation and modification.

## Features

- **Diamond Detection:**  
  Uses template matching to locate the diamond in each frame.
  
- **Skull Detection & Tracking:**  
  When the diamond is hidden under a skull, the model identifies the covering skull using contour detection and tracks its movement using the CSRT tracker.
  
- **Output Video:**  
  Annotates the video with bounding boxes around the detected diamond (green) and skull (red), and saves the result as an MP4 file.

## Requirements

- Python 3
- [Google Colab](https://colab.research.google.com/) (recommended for ease of use)
- OpenCV packages:
  - `opencv-python`
  - `opencv-contrib-python`

## Installation

To install the necessary dependencies, run the following command in a Colab cell:

```bash
!pip install opencv-python opencv-contrib-python
