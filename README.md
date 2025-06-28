# brightness_detection
A lightweight Python tool that reads images, converts to grayscale, and applies Gaussian blur. It calculates overall brightness via average pixel intensity and finds brightest regions using cv2.minMaxLoc. It flags under/overexposed images based on thresholds—ideal for basic image quality checks.
