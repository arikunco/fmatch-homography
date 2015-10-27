## About Feature Matching and Homography
This code is one of assignment from Prof Widodo Budiharto (Machine Vision Class) to create an object detection and feature matching using FLANN. This code is adaptation of tutorial publshed in http://docs.opencv.org/3.0-beta/doc/py_tutorials/py_feature2d/py_feature_homography/py_feature_homography.html, accessed on October 27, 2015. Somehow the code written in tutorial is not running well on my environment (I guess due to different version of Python). 

## Requirements 
1. Python (tested in 2.7.6). 
2. OpenCV 3.0. 
3. Python packages: numpy and matplotlib. 
4. Extra modul for SIFT function. (http://stackoverflow.com/questions/28000772/install-opencv-3-0-with-extra-modules-sift-surf-for-python)

## How to Run
Simply do this command: 

```python
python FMHomograpy.py
```

Tips: Play around with the resize value in this script: 
```python
##You probably need to resize the image 
img1 = cv2.resize(img1, (0,0), fx=0.3, fy=0.3) 
img2 = cv2.resize(img2, (0,0), fx=0.2, fy=0.2) 
```
## Result Sample: 

Green lines are the associated marking for train and query image. The more green lines drawn, the more certain object detection is. Object is marked in white color in cluttered image. 

![alt text](https://raw.githubusercontent.com/arikunco/fmatch-homography/master/result_samsung.jpg "Test Smartphone 1")

![alt text](https://raw.githubusercontent.com/arikunco/fmatch-homography/master/result_samsung2.jpg "Test Smartphone 1")

![alt text](https://raw.githubusercontent.com/arikunco/fmatch-homography/master/result_tnt.jpg "Test Trinity Book")

## Message
Selamat mencoba, ya! Good luck!
If you have some difficulties or inputs, kindly let me know. 

Salam, Ari. 
http://arikuncoro.wordpress.com




