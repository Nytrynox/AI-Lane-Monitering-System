# AI Lane Monitoring System

## Overview
An advanced driver assistance system (ADAS) feature that uses computer vision to detect lane markings on the road. It provides real-time alerts to drivers if they drift out of their lane, enhancing road safety.

## Features
-   **Lane Detection**: Robust identification of road lane lines using edge detection.
-   **Curvature Calculation**: Estimates the radius of road curvature.
-   **Offset Measurement**: Determines the vehicle's position relative to the lane center.
-   **Visual Overlay**: Draws detected lanes and metrics directly onto the video feed.

## Technology Stack
-   **Vision**: OpenCV.
-   **Language**: Python.
-   **Algorithm**: Sliding Window technique / Hough Transform.

## Usage Flow
1.  **Input**: System takes a video stream from a dashboard camera.
2.  **Preprocess**: Image is warped, color-corrected, and filtered.
3.  **Detect**: Lane pixels are identified and fitted to a polynomial.
4.  **Display**: Processed frame with lane overlay is shown to the user.

## Quick Start
```bash
# Clone the repository
git clone https://github.com/Nytrynox/AI-Lane-Monitoring-System.git

# Install dependencies
pip install opencv-python numpy matplotlib

# Run the detector
python main.py
```

## License
MIT License

## Author
**Karthik Idikuda**
