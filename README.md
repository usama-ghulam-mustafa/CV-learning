# WEEK 1-2

## Topics Covered
- Image array structure (shape, dtype)
- RGB channel manipulation
- Grayscale conversion
- Cropping and flipping
- Brightness adjustment and uint8 overflow handling
- Pixel histograms
- Binary masking
- Normalization
- NumPy core — shape, dtype, slicing, masking, broadcasting, normalization
- Images as matrices — PIL, matplotlib, HWC convention, channel splitting
- Image operations — cropping, flipping, rotation, brightness, contrast, histogram

# Week 3 - OpenCV & Classical Computer Vision
## Topics Covered
**Color Spaces**
- BGR vs RGB — why OpenCV uses BGR and when to convert
- Color space conversions: RGB, HSV, Grayscale
**Image Filtering**
- Manual convolution from scratch using NumPy
- Gaussian blur, Median blur, Bilateral filter
- When to use each filter and why
**Edge Detection**
- Sobel edge detection (horizontal and vertical)
- Canny edge detection and hysteresis thresholding
- Laplacian of Gaussian (LoG)
- Comparison of all three methods
## Key Concepts
- Kernel values summing to 1 vs 0 and what each produces
- Bilateral filter preserves edges while blurring flat regions
- Median blur is best for salt and pepper noise
- Canny thresholds control precision vs recall tradeoff
- Zero crossings in LoG mark exact edge locations
