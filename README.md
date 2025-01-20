# Digital_Image_Processing

#  RGB2Gray
This project demonstrates image processing in MATLAB by extracting and visualizing individual color channels (Red, Green, Blue) and converting images to grayscale. The script reads an input image, isolates specific color channels by manipulating pixel values, and displays the results for analysis. It also showcases grayscale conversion using the rgb2gray function.

Features
Extract Red, Green, and Blue channels.
Convert images to grayscale using two methods.
Usage
Place an image file (e.g., car.jpg) in the script's directory, run it in MATLAB, and view the output visualizations.




# Image Histogram Equalization Analysis

This repository contains MATLAB scripts for performing and visualizing histogram equalization on grayscale images to enhance contrast. Two methods are implemented:

1. **Manual Histogram Equalization**: Calculates the histogram, cumulative distribution function (CDF), and applies the transformation manually to equalize the image.
2. **Built-in Function (`histeq`)**: Utilizes MATLAB's `histeq` function for an automated approach to histogram equalization.

Both methods include comprehensive visualizations that compare the original and equalized images, histograms, and CDFs, arranged in a 2x3 subplot format. These visualizations help illustrate the impact of histogram equalization on image contrast.

### Usage:
1. Clone the repository and replace the placeholder image with your own.
2. Run the respective scripts:
   - `manual_histogram_equalization.m`
   - `builtin_histogram_equalization.m`

### Requirements:
- MATLAB R2021a or later

This repository is ideal for understanding histogram equalization concepts and exploring contrast enhancement techniques.
