# Road-Lane-Detection-System
Real-time road lane detection system built with Python and OpenCV. Utilizes Canny edge detection and Hough Transform to identify lane boundaries in driving footage.

Frame Pre-processing: Converts frames to grayscale and applies Gaussian Blur to reduce noise before edge detection.

Region of Interest (ROI): Defines a custom polygonal mask to focus processing exclusively on the driving lane, optimizing performance.

Lane Integration: Uses cv2.addWeighted to overlay detected lines onto the original footage for a clear augmented reality output.

Video Output: Successfully processed and exported 300 frames of high-definition road footage to Google Drive as an .avi file.





