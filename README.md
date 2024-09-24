Edge Detection Using Gaussian and Derivative Filters
This script performs edge detection on an input image using Gaussian smoothing, edge detection with Gaussian derivative kernels, and non-maximum suppression. It processes the image in several steps:

Gaussian smoothing is applied to reduce noise.
Edge detection is performed using the derivative of Gaussian.
Gradient magnitude is calculated to identify edge strength.
Non-maximum suppression refines the edges by keeping only the strongest edges.
Hysteresis thresholding is used to finalize the edge detection by connecting weak edges to strong ones.
The script visualizes each step of the process for better understanding.
