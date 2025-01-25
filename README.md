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


# Bit Plane Slicing 

This MATLAB project demonstrates **Bit Plane Slicing**, a technique used to analyze and visualize the contribution of each bit in a grayscale image's pixel intensity. The script processes an input image and extracts its 8-bit planes, from the Least Significant Bit (LSB) to the Most Significant Bit (MSB).

#### Features:
1. **Image Conversion**: Converts a color image to grayscale using `rgb2gray`.
2. **Bit Plane Extraction**: Utilizes `bitget` to isolate individual bit planes.
3. **Visualization**: Displays each bit plane as an image for better understanding.
4. **Customizable Input**: Replace the path in `imread` with your image path.

