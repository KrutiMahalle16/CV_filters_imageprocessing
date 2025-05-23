# CV_filters_imageprocessing
# Image Filtering Analysis

This project focuses on applying and analyzing the effects of **Gaussian**, **Sobel**, and **Median** filters on digital images. The goal is to demonstrate the distinct functionalities and use-cases of these filters in the fields of noise reduction, edge detection, and noise removal.

## Objective

To explore and understand how different image filters affect digital images by:

* Reducing noise using Gaussian filtering
* Detecting edges using Sobel filtering
* Removing noise using Median filtering

### Technologies Used

OpenCV: For image processing operations
NumPy: For numerical computations
Matplotlib: For visualizing the filtered images

## Filters Overview

### 1. Gaussian Filter

* Purpose: **Noise reduction**
* Mechanism: Applies a Gaussian kernel to smooth the image
* Result: Softens the image and reduces high-frequency components

### 2. Sobel Filter

* Purpose: **Edge detection**
* Mechanism: Calculates the gradient of the image intensity in horizontal and vertical directions
* Result: Highlights regions of high spatial gradient (edges)

### 3. Median Filter

* Purpose: **Noise removal**
* Mechanism: Replaces each pixel's value with the median value of its neighboring pixels
* Result: Effective in removing salt-and-pepper noise while preserving edges

  
### Usage

Load an image using OpenCV

Apply each of the filters using OpenCV functions:
cv2.GaussianBlur()
cv2.Sobel()
cv2.medianBlur()
Visualize the results using Matplotlib
Compare the outcomes to analyze the strengths of each filter


### Conclusion

By analyzing the filtered images, you can clearly see how:
Gaussian filter smoothens and reduces random noise
Sobel filter emphasizes the edges and contours
Median filter effectively removes impulse noise without blurring edges
This project helps build a foundational understanding of classical filtering techniques in image processing.



