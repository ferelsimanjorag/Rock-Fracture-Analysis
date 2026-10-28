# Rock Fracture Analysis (Borehole Image Processing)

This repository contains two mini-projects focused on automating the detection and segmentation of rock fractures, simulating workflows for borehole image log analysis.

## Projects Overview

### 1. OpenCV Workflow Automation (`Project_1.ipynb`)
* **Goal**: Detect fracture lines using traditional computer vision techniques.
* **Methods**: Applied Grayscale conversion, local contrast enhancement simulating dynamic image logs (CLAHE), and Canny Edge Detection.
* **Feature**: Built a `for` loop to batch-process multiple images automatically.

### 2. AI Image Segmentation (`Project_2.ipynb`)
* **Goal**: Isolate intact rock fragments and identify fracture paths using Deep Learning.
* **Methods**: Utilized **FastSAM** (Segment Anything Model via Ultralytics) to generate segmentation masks.
* **Feature**: Tuned confidence thresholds to filter out textural noise, providing cleaner structural insights compared to classical edge detection.

## Tools & Libraries
* Python 3
* OpenCV (`cv2`)
* Ultralytics (FastSAM)
* Matplotlib
