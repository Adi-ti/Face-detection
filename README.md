# Face-detection
The prime concern of this project is to read and display a reltime video.
a. Numpy 
b. cv2
to download this in python simply write pip install numpy and pip install cv2 in cmd.
First we have to import numpy as it helps to represent images in a multidimensional array then we will import cv2 which is a library of python. We use while (True) because we want to run the program and start taking images until waitkey is used. Actually this is used to capture real time video without stopping. Then to use face detection we preferred to convert BGR to gray to reduce noise and to convert 3dimensional array to 2 dimensional array. Then to read an image, we use imread which means image read which is generally stored in n dimensional array. For example:
Image = cv2.imread(‘File path’)
As we do not use semicolon in python like c. Then to display an image we read before, we use imshow function:
Cv2.imshow(‘Image name’,image)
Generally, we use waitkey function to  wait for a few milliseconds  This is used so that user’s input can be taken from keyboard. Then we have to release the camera so that camera is able to read and display a real time video stream. At last we have to destroy all windows and the only active thing in laptop is the running real time video.
If one has to do eye detection then he/ she must have to use ROI also known as region of interest. So that system will detect only those things which is a region of interest like eyes.
This is the basic of computer vision.  

