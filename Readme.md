## Thresholding

The simplest thresholding methods replace each pixel in an image with a black pixel if the image intensity {\displaystyle I_{i,j}}I_{{i,j}} is less than some fixed constant T (that is, {\displaystyle I_{i,j}<T}I_{{i,j}}<T), or a white pixel if the image intensity is greater than that constant. In the example image on the right, this results in the dark tree becoming completely black, and the white snow becoming completely white

## Otsu thresholding
Otsu's method is used to perform automatic image thresholding.In the simplest form, the algorithm returns a single intensity threshold that separate pixels into two classes, foreground and background.

## Niblack thresholding
This is an implementation of a traditional Niblack local image thresholding with an integral image method, which guarantees constant computation time regardless of the neighborhood size.

## Sauvola thresholding
The implemented Sauvola method uses integral images for fast computation of the threshold function.

## Clean Image adding Noise(image)

Screen Shot
-----------------------
<img src="https://github.com/GK-CPP/Image-Processing/blob/master/images/in_1.jpg">
<p align="center"><b>Clean Image</b></p>
<img src="https://github.com/GK-CPP/Image-Processing/blob/master/images/nos_1.JPG">
<p align="center"><b>Noise</b></p>
<img src="https://github.com/GK-CPP/Image-Processing/blob/master/images/out_1.png">
<p align="center"><b>Clean image adding Noise(image)</b></p>