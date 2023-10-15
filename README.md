# Canny Edge Detection from scratch

This project implements Canny Edge Detection from scratch, a fundamental image processing technique that identifies edges in images. The process involves five main steps:

1. **Grayscale Conversion**: Color images are converted to grayscale, making edge detection simpler.

2. **Gaussian Blurring**: The image is filtered with a Gaussian kernel to reduce noise, enhancing edge detection accuracy.

3. **Gradient Estimation**: The strength and direction of gradients are estimated using Sobel filters.

4. **Non-Maximum Suppression**: We ensure that edges are one pixel thick by suppressing non-maximum gradients along the gradient's normal direction.

5. **Dual Thresholding**: Finally, strong gradient pixels are connected using a dual threshold to create the final edge image.

## Usage

You can use this Canny Edge Detection implementation with your own images. Simply replace `image_name` with the path to your image and adjust the threshold values if needed.

## Result

The result is a one-pixel thick edge-detected image with clear and well-connected edges.

Original Image             |  Canny Edge Detection
:-------------------------:|:-------------------------:
![Original Image](cat.jpeg)  |  ![Canny Edge Detection Result](Canny%20Edge%20Detection_cat.jpeg)

## OpenCV Comparison

I provide a comparison with OpenCV's Canny Edge Detection to verify my implementation's accuracy.

## Dependencies

- Python
- OpenCV
- NumPy
- Matplotlib

## Author

Shanaaz Ahamed

## License

This project is open-source under the [MIT License](LICENSE). Feel free to use, modify, and share.

---
[GitHub Repository Link](https://github.com/imshaaz21/CannyEdgeDetection)
