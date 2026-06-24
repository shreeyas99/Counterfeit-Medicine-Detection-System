# Counterfeit Medicine Detection System

## Overview

The Counterfeit Medicine Detection System is an AI-powered healthcare solution designed to identify counterfeit medicines using Computer Vision and Embedded Systems. The project utilizes Raspberry Pi 5, OpenCV, and YOLOv8 to analyze medicine packaging and classify products as genuine or counterfeit in real time.

## Problem Statement

Counterfeit medicines are a major threat to public health and pharmaceutical safety. Traditional verification methods are often time-consuming, expensive, and inaccessible. This project aims to provide a portable, automated, and cost-effective solution for medicine authentication using Artificial Intelligence.

## Objectives

- Develop a portable medicine authentication system.
- Detect counterfeit medicines using Computer Vision techniques.
- Implement real-time image processing on Raspberry Pi.
- Improve healthcare safety through automated verification.
- Explore the application of Edge AI in pharmaceutical authentication.

## Components Used

### Hardware
- Raspberry Pi 5
- Raspberry Pi Camera Module
- Micro SD Card
- Power Supply
- Display Monitor (Optional)

### Software
- Python
- OpenCV
- YOLOv8
- NumPy
- Google colab
- VS Code

## Working

1. The medicine package image is captured using the Raspberry Pi Camera Module.
2. The captured image is preprocessed using OpenCV.
3. The trained YOLOv8 model extracts and analyzes visual features.
4. The system compares the detected features against trained data.
5. The medicine is classified as Genuine or Counterfeit.
6. The result is displayed to the user in real time.

## Results

- Successfully developed a working prototype.
- Achieved approximately 85% classification accuracy.
- Demonstrated real-time medicine verification capability.
- Validated the feasibility of AI-powered counterfeit medicine detection.

## Applications

- Pharmaceutical Industry
- Hospitals and Clinics
- Medical Supply Chain Verification
- Drug Inspection Agencies
- Healthcare Research

## Future Scope

- Integration of Near-Infrared (NIR) Spectroscopy.
- Development of a mobile application interface.
- Cloud-based medicine database integration.
- QR code and barcode authentication support.
- Improved detection accuracy using larger datasets.
- Multi-class counterfeit medicine classification.
