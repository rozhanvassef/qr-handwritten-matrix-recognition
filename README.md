# qr-handwritten-matrix-recognition
A machine learning system for recognizing handwritten matrices and performing QR decomposition through image processing and deep learning techniques.


## Overview

This project implements a complete pipeline for recognizing handwritten matrices from images and computing their QR decomposition. The system combines computer vision, OCR, and numerical linear algebra to process handwritten mathematical content.

## Project Components

### 1. EMNIST Dataset (`1-0`)
- Comprehensive digit and character dataset for training recognition models
- Preprocessing and data augmentation pipelines

### 2. Hough Transform Analysis (`2-0`)
- Matrix detection and grid extraction from images
- Line and structure detection for matrix boundaries

### 3. QR Decomposition using Hough Matrices (`3-0`)
- Extract matrix elements using Hough transform results
- Perform QR decomposition on recognized numerical matrices

### 4. Convolutional Neural Networks (`4-0`)
- Deep learning models for digit and character recognition
- CNN architectures optimized for handwritten content

### 5. QR Decomposition using CNN Matrices (`5-0`)
- End-to-end pipeline: image → CNN recognition → QR decomposition
- Integration of recognition and numerical computation

### 6. Accuracy Comparison (`6-0`)
- Comparative analysis of two methods for QR decomposition
- Evaluation metrics: recognition accuracy, decomposition error, computational efficiency

## Features

- **Image Preprocessing**: Noise reduction, normalization, and enhancement
- **Matrix Detection**: Automated grid detection using Hough transforms
- **Character Recognition**: CNN-based OCR for handwritten digits and symbols
- **QR Decomposition**: Numerical computation on recognized matrices
- **Dual Pipeline**: Both traditional (Hough) and deep learning (CNN) approaches
- **Performance Analysis**: Comprehensive comparison and evaluation
