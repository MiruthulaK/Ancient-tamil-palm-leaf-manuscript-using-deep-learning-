# Deep Neural Architecture for Ancient Tamil Palm Leaf Character Recognition

## Overview

Ancient Tamil palm leaf manuscripts contain valuable historical and
cultural information. However, recognizing handwritten Tamil characters
from these manuscripts is challenging due to noise, degradation, fading
ink, and variations in handwriting styles.

This project proposes a deep learning--based pipeline to process palm
leaf manuscript images and recognize Tamil characters. The system
focuses on improving image quality, extracting individual characters,
and preparing them for accurate recognition.

## Project Pipeline

The workflow of the system consists of the following stages:

1.  **Image Preprocessing**
    -   Clean and enhance manuscript images to improve readability.
2.  **Character Extraction**
    -   Detect and isolate individual Tamil characters from the
        manuscript images.
3.  **Character Recognition**
    -   Use deep learning models to classify Tamil characters.
4.  **Web Interface**
    -   A simple web application to upload palm leaf images and view
        processed outputs.

## My Contribution -- Image Processing

I worked on the **image processing pipeline** of the project.

-   Implemented **U-Net based binarization** to convert grayscale
    manuscript images into black-and-white format, reducing background
    noise.
-   Applied **FSRCNN (Fast Super-Resolution Convolutional Neural
    Network)** to enhance the resolution and clarity of binarized
    images.
-   Used **OpenCV contour detection** to generate **bounding boxes** and
    extract individual Tamil characters from the manuscripts.

## Challenges Faced

-   Palm leaf images were often **highly degraded and noisy**.
-   **Inconsistent lighting and faded ink** made character detection
    difficult.
-   **Overlapping characters** required careful bounding box tuning.
-   Limited availability of **annotated Tamil palm leaf datasets**
    required manual verification and adjustments.

## Technologies Used

-   Python
-   U-Net (Deep Learning for Image Segmentation)
-   FSRCNN (Super Resolution Model)
-   OpenCV
-   Deep Learning / CNN models

## Keywords

U-Net, FSRCNN, OpenCV, Image Processing, Character Segmentation,
Historical Document Analysis





