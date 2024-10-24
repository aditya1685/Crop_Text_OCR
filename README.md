The Project mainly focuses changing the perspective of image and getting it perfectly aligned to window. 


This is accomplished with use of perspective transform in OpenCV.


One thing one should note before using this code is the choice of coordinate points. 


the sequence to follow is 
1. Upper left corner
2. lower left corner
3. lower right corner
4. Upper right corner

after the image is cropped perfectly, I have used pytessaract for OCR, which might give some wrong predictions if the image quality is not so good. 
