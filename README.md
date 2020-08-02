# Advanced Lane Finding

An opencv-based implementation of a self-driving car module responsible for detecting lane lines under different lighting conditions, pavement textures and curves.

**Implementation includes the following:** 

- Camera calibration and distortion correction.
- Applying Gaussian Blur.
- Edge Detection using Sobel.
- Color/gradient thresholding.
- Perspective transform.
- Detecting lane lines using peaks of histogram and sliding window.
- Drawing lanes on the original image
- Determining the lane curvature.


## Dependencies:
1. `pip install numpy`
2. `pip install matplotlib`
3. `pip install opencv-python`
