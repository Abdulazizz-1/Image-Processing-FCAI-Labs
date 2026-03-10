# Image Processing Lab: Contrast Stretching

This repository contains a Python implementation of Contrast Stretching, developed as part of an Image Processing laboratory experiment at Cairo University (FCAI). The script demonstrates the enhancement of low-contrast images by stretching their intensity values across the full dynamic range.

## Objective
The primary goals of this experiment are to:
1. Extract the minimum ($r_{min}$) and maximum ($r_{max}$) pixel intensities from the original image histogram.
2. Apply the linear contrast stretching transformation to map the pixel values to the full $[0, 255]$ range.
3. Utilize OpenCV's Look-Up Table (`cv2.LUT`) mapping for computationally efficient, vectorized processing.

## Dependencies
* **Python 3.x**
* **OpenCV (`cv2`)**: For image I/O operations, histogram calculations, and LUT application.
* **NumPy**: For matrix manipulation and efficient LUT generation.
* **Matplotlib**: For visualizing the original and transformed images alongside their respective histograms.

## Results & Observations
Applying this transformation to the sample image effectively redistributes the pixel intensities. The resulting histogram spans the entire 0 to 255 range, which quantitatively and qualitatively improves the visibility of fine details within the image. Sample output plots and visual comparisons are provided in the repository for reference.
