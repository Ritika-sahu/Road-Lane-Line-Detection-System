# Road-Lane-Line-Detection-System
In this project, I used Python and OpenCV to detect lane lines on the road. I developed a processing pipeline that works on a series of individual images, and applied the result to a video stream.

# Pipeline architecture:
Load test images.
Apply Color Selection
Apply Canny edge detection.
Apply gray scaling to the images.
Apply Gaussian smoothing.
Perform Canny edge detection.
Determine the region of interest.
Apply Hough transform.
Average and extrapolating the lane lines.
Apply on video streams.