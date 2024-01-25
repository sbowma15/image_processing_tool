# image_processing_tool

The script provides a set of image processing techniques, including smoothing, edge detection using Sobel filters, and contour extraction. The script combines OpenCV and NumPy functionalities to perform these operations on an input image. The primary focus is on enhancing images and extracting contours for further analysis.

Functions

1. Smoothing
smooth_image(image_path): Reads an image from a specified path, converts it to grayscale, and applies Gaussian smoothing. Displays the original and smoothed images.
2. Edge Detection
edge_detection(image_path): Reads an image from a specified path, converts it to grayscale, and applies Sobel filters for horizontal and vertical edge detection. Displays the gradient magnitude.
3. Contour Extraction
extract_contours(image_path): Reads an image from a specified path, applies dilation and erosion to enhance shapes, and attempts to find contours. Displays the image with detected contours.

This script serves as a versatile tool for basic image processing tasks, providing functions for smoothing, edge detection, and contour extraction. The functions can be adapted for various image analysis applications.






