Lab Title

Image Segmentation Techniques using Python

Objectives of the Lab

The main objectives of this lab are:

To understand the basic concept of image segmentation.

To apply global, local, and adaptive thresholding on grayscale images.

To perform K-means clustering based image segmentation for different values of k.

To implement Mean Shift segmentation for region-based segmentation.

To visually compare different segmentation techniques.

To analyze the strengths and weaknesses of each segmentation method.

To gain hands-on experience using Python, OpenCV, and Matplotlib.

Tools and Software Used

Google Colab / Jupyter Notebook

Python 3

OpenCV (cv2)

NumPy

Matplotlib

Theory (Short & Easy)

Image segmentation is the process of dividing an image into multiple meaningful regions so that objects in the image can be easily analyzed. Each segment contains pixels with similar properties such as color, intensity, or texture.

Types of Segmentation Used

Thresholding: Separates objects from background based on pixel intensity.

Clustering-based Segmentation: Groups similar pixels using algorithms like K-means.

Region-based Segmentation: Groups pixels based on density and similarity (Mean Shift).

Methodology / Tasks Performed

The following steps were performed in this lab:

Load the input image and convert it to grayscale.

Apply Global Thresholding using a fixed threshold value.

Apply Local Thresholding using neighborhood-based thresholding.

Apply Adaptive Thresholding to handle varying illumination.

Perform K-means segmentation with:

k = 2

k = 3

k = 4

Perform Mean Shift segmentation for smooth region separation.

Display all segmentation results using Matplotlib.

Compare all methods visually.

Results and Observations

Global thresholding works well only when lighting is uniform.

Adaptive thresholding gives better results in uneven lighting conditions.

K-means segmentation effectively separates regions based on color and intensity.

Increasing the value of k increases segmentation detail.

Mean Shift segmentation produces smooth and natural-looking regions but is computationally expensive.

Strengths of Each Method
Method	Strength
Global Thresholding	Simple and fast
Adaptive Thresholding	Handles uneven lighting
K-means	Effective color-based segmentation
Mean Shift	Produces smooth regions
Limitations

Thresholding methods are sensitive to noise.

K-means requires manual selection of k.

Mean Shift is slower for large images.

Applications of Image Segmentation

Medical image analysis

Object detection

Face recognition

Satellite image processing

Autonomous vehicles

Conclusion

In this lab, various image segmentation techniques were successfully implemented and analyzed. Each method has its own advantages and limitations depending on image conditions. Adaptive thresholding and clustering-based methods provide better segmentation results compared to simple thresholding. This lab helped in understanding practical segmentation techniques using Python.
