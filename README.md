# Face-Detection-with-Haar-Cascades

The purpose of this project is to show how to use OpenCV, Face Haar Cascades, and your webcam to create a simple Face Detection program

## Haar Cascade Basics
Haar Cascades use features to calculate contrast between a group of pixels. As such, they can then be trained recognize that certain pixel contrast combinations can commonly represent facial features.
For example, an eye can often be simplied as having a horizontal white-black-white pixel group pattern due to the white background, black iris, and white background of the eye.
For this Face Detection model, three pre-trained Haar Cascades were used for detecting the face, eyes, and smile. OpenCV was the library utilized to extract the cascades.

## Detect Function
The purpose of the Detect function is take the frames of the video and visualize the region of interest detected by the cascade.
First a rectangle is animated around the detected face by grabbing the x,y, width, and height coordinates from the cascade results. Then within this rectangle, more rectangles are created for the detected eyes and smile.

## Processing
OpenCV can access the user's webcam. As such, the results of the Detect function can be seen live while the webcam was on.

## Results
Please find results in the following link: https://hjmok.github.io/josephmok_portfolio/#/FD 
