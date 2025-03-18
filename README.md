# exp-5

Sobel Operator detects edges by calculating gradients in both horizontal and vertical directions using 3x3 kernels.
The horizontal Sobel kernel detects vertical edges, while the vertical Sobel kernel detects horizontal edges.
The gradient magnitude is computed by combining the results from both kernels, highlighting areas of intensity change.
Sobel is more sensitive to noise due to its 3x3 kernel, making it useful for detecting sharp edges.
Prewitt Operator is similar to Sobel but uses different 3x3 kernels for edge detection.
The horizontal Prewitt kernel detects vertical edges, and the vertical Prewitt kernel detects horizontal edges.
Prewitt is generally less sensitive to noise than Sobel, providing smoother edge detection.
Both operators are widely used for edge detection in image processing, with Sobel often preferred for noisy images.
