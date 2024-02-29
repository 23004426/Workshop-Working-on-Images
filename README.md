# Workshop-Working-on-Images
### AIM :
The image should be converted to gray scale and HSV and display the H, S and V planes.

### Software Required :
jupyter Notebook

### Algorithm :
### Step1:
Choose an image , the image should be a plant , Tree, flower or building.
### Step 2:
Save the image and the filename should be username.jpg
### Step 3:
Convert the image to gray scale and HSV
### Step 4:
Display the H,S and V planes.

### PROGRAM:
```
Developed by:Tirupathi Jayadeep
Register number: 212223240169

import cv2
import numpy as np
image = cv2.imread("jayadeep.jpg")
image = cv2.resize(image,(300,200))
gray = cv2.cvtColor(image, cv2.COLOR_BGR2GRAY)
hsv = cv2.cvtColor(image, cv2.COLOR_BGR2HSV)
h, s, v = cv2.split(hsv)
cv2.imshow("Hue (H)", h)
cv2.imshow("Saturation (S)", s)
cv2.imshow("Value (V)", v)
cv2.waitKey(0)
cv2.destroyAllWindows()
```
### OUTPUT:
![image](https://github.com/23004426/Workshop-Working-on-Images/assets/144979327/fcca3a2d-ad38-4cb2-a7b4-87ee77d609ce)

### RESULT:
Thus the image is converted to gray scale and HSV using python and displayed successfully.

