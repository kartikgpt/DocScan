# DocScan
A simple document scanner developed with OpenCV that detects the largest contour in the image and then converts the skewed part of the contour to 
unskewed (straight) image.


The steps that we need to follow to build this project are:

1. Convert the image to grayscale
2. Find the edges in the image
3. Use the edges to find all the contours
4. Select only the contours of the document
5. Apply warp perspective to get the top-down view of the document.

Necessary Packages:

1. pip install imutils
2. pip install scipy
3. pip install opencv-python
