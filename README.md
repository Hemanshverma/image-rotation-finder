# Image-Rotation-Finder

This repo contains a single .pynb file with a function named calculate image. Which uses OpenCV with SIFT to find the key points in both the images. Then uses their image description and key points to find the matches between 2 images. It then takes the matches and find some random matched coordinates into both the images and then uses those coordinates to find the new angle of image.

Usage:

```python
from cv2 import imread
import cv2
from math import atan2
path1='a.jpg'
path2='a1.jpg'
calculate_angle(path1,path2) # returns the angle of rotation by which image2 is rotated
```



