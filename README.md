# Advanced Image Encryption using Magic Squares and Chaos

## Overview
This project implements a secure image encryption and decryption system for color images by combining multiple techniques:
- Magic Square scrambling
- 2D Arnold Transform for pixel permutation
- Logistic chaotic maps for pseudo-random sequence generation
- Differential encoding
- XOR and circular shift operations

## Features
- Encrypt and decrypt color images with robust chaos-based algorithms
- Analyze encryption quality with:
  - Correlation plots (horizontal, vertical, diagonal)
  - PSNR and SSIM metrics
  - Information entropy calculation
  - NPCR and UACI to measure sensitivity and diffusion
  - Histogram comparison of original and encrypted images

## Usage
1. Upload an image (preferably square and 256x256 for best results).
2. Run the encryption function to get the encrypted image.
3. Run the decryption function to recover the original image.
4. Visualize and analyze encryption quality with provided plots and metrics.

## Requirements
- Python 3.x
- numpy
- opencv-python
- matplotlib
- scikit-image
- Google Colab (optional for file upload)

## How to Run
```python
# Upload image using Google Colab
from google.colab import files
uploaded = files.upload()

# Load image, encrypt, decrypt, and visualize results
# (Use provided code in the main script)

