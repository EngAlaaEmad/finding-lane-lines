# finding-lane-lines

##Project for Udacity Self-Driving Car Nanodegree

This is a project I created for the Udacity Self-Driving Car Engineer Nanodegree. The goal was to build a pipeline of image processing functions that takes a road image / video as input and outputs the image / video with lane lines marked with straight red lines.

The pipeline consists of 7 steps:
- Conversion to grayscsale
- Gaussian blur
- Canny edge detection
- Selection of region of interest
- Hough transformation
- Extrapolation of the Hough lines
- Adding the lane lines to the original image

The functions are implemented using the NumPy and matplotlib libraries. The pipeline is demonstrated below with the outputs of each step:

![alt text][./finding_lane_lines/images/original.png]
