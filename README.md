This notebook addresses two main challenges related to image processing:

## Challenge 1: Implement Histogram Equalization and Contrast-Limited Adaptive Histogram Equalization (CLAHE)

1. **Implementation of Classic Methods:** 
   - Histogram Equalization and CLAHE are implemented on a set of medical images.
   - The code provides a comparison and evaluation of the image quality after applying these enhancement techniques.

2. **Interactive Image Display:**
   - Functions such as `hiseq_clahe` and `HE_CL` are defined for visualizing the effects of Histogram Equalization and CLAHE.
   - The notebook shows the original image, the image after histogram equalization, and the image after CLAHE for multiple medical images.

3. **Adjusting CLAHE Parameters:**
   - The notebook explores the impact of changing CLAHE parameters such as `clipLimit` and `tileGridSize`.
   - Different clipLimit and tileGridSize values are applied to the images, and the results are visualized.

## Challenge 2: Implement Filtering Methods (Mean, Median, Gaussian)

1. **Implementation of Filtering Methods:**
   - Mean filter, Median filter, and Gaussian filter are implemented using OpenCV.
   - The notebook visually compares and evaluates the image processing results before and after applying these filters for different kernel sizes.

2. **Exploring Different Kernels and Sigma Values:**
   - The notebook investigates the effects of different kernel sizes and sigma values for Gaussian blur.
   - Images are displayed with varying kernel sizes (5x5, 7x7, 9x9) for mean, median, and Gaussian filters.
   - The impact of different sigma values in Gaussian blur is also demonstrated.

3. **Adding Noise for Robustness Testing:**
   - The filtering methods are tested for robustness by adding salt and pepper noise to the images.
   - The performance of the filters under noisy conditions is evaluated.

## How to Use:
- Each section in the notebook is dedicated to a specific challenge or aspect of the image processing tasks.
- Run the cells sequentially to see the results and visualizations.
- Interact with the code to explore different parameters and observe their effects on image enhancement and filtering.

Feel free to use this notebook as a reference for implementing image enhancement techniques and filters in the context of medical image processing.
