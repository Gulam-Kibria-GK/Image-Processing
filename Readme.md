# 🖼️ Image Processing

This repository explores various **image processing techniques** such as thresholding, noise addition, reconstruction, and **deep learning using autoencoders**, implemented in Python.


## ✅ Thresholding Techniques

### 🔹 Basic Thresholding
The simplest thresholding methods replace each pixel in an image with:
- **Black** if intensity \( I_{i,j} < T \)
- **White** if intensity \( I_{i,j} \geq T \)


### 🔹 Otsu Thresholding
Otsu's method automatically calculates the optimal threshold to separate an image into **foreground** and **background**. It maximizes the variance between the two classes.  
📄 [Otsu thresholding for multiple image.ipynb](https://github.com/Gulam-Kibria-GK/Image-Processing/blob/master/Otsu%20thresholding%20for%20multiple%20image.ipynb)


### 🔹 Niblack Thresholding
Niblack’s method performs **local thresholding**, calculating the threshold value for each pixel based on the local mean and standard deviation.  
📄 [Niblack thresholding for skimage data.ipynb](https://github.com/Gulam-Kibria-GK/Image-Processing/blob/master/Niblack%20thresholding%20for%20skimage%20data.ipynb)


### 🔹 Sauvola Thresholding
An improvement over Niblack's method, Sauvola’s approach uses local statistics but provides better performance on documents and noisy images.  
📄 [Sauvola thresholding for skimage data.ipynb](https://github.com/Gulam-Kibria-GK/Image-Processing/blob/master/sauvola%20thresholding%20for%20skimage%20data.ipynb)


## 🧪 Clean Image with Noise Added

<table>
  <tr>
    <td><img src="https://github.com/GK-CPP/Image-Processing/blob/master/images/in_1.jpg" width="300" height="400"></td>
    <td><img src="https://github.com/GK-CPP/Image-Processing/blob/master/images/nos_1.JPG" width="300" height="400"></td>
    <td><img src="https://github.com/GK-CPP/Image-Processing/blob/master/images/out_1.png" width="300" height="400"></td>
  </tr>
  <tr>
    <td><b>Clean Image</b></td>
    <td><b>Added Noise</b></td>
    <td><b>Output with Noise</b></td>
  </tr>
</table>

📄 [Clean Image adding Noise(image) using CV2.ipynb](https://github.com/Gulam-Kibria-GK/Image-Processing/blob/master/Clean%20Image%20adding%20Noise(image)%20using%20CV2.ipynb)


## 🔍 Image Resize with Padding

Resize an image to a specific dimension while maintaining aspect ratio by adding padding (scaling up).  
📄 [Image scale Up using padding(Resize).ipynb](https://github.com/Gulam-Kibria-GK/Image-Processing/blob/master/Image%20scale%20Up%20using%20padding(Resize).ipynb)


## 🧩 Image Crop and Reconstruction

<table>
  <tr>
    <td><img src="https://github.com/GK-CPP/Image-Processing/blob/master/images/in_2.png" width="300" height="400"></td>
    <td><img src="https://github.com/GK-CPP/Image-Processing/blob/master/images/mid_2.png" width="300" height="400"></td>
    <td><img src="https://github.com/GK-CPP/Image-Processing/blob/master/images/in_2.png" width="300" height="400"></td>
  </tr>
  <tr>
    <td><b>Original Image</b></td>
    <td><b>Cropped Part</b></td>
    <td><b>Reconstructed Image</b></td>
  </tr>
</table>

📄 [Image_Crop_and_Reconstructed.ipynb](https://github.com/Gulam-Kibria-GK/Image-Processing/blob/master/Image_Crop_and_Reconstructed.ipynb)


## 🧠 Autoencoder

### 🔹 Autoencoder for Variable-Size Images
This model handles input images of varying sizes using a custom-built CNN-based autoencoder.  
📄 [Final Autoencoder.ipynb](https://github.com/Gulam-Kibria-GK/Image-Processing/blob/master/Autoencoder%20for%20variable%20size%20images/Final%20Autoencoder.ipynb)  
💾 [Model_pc3_1.h5](https://github.com/Gulam-Kibria-GK/Image-Processing/blob/master/Autoencoder%20for%20variable%20size%20images/Model_pc3_1.h5)


### 🔹 Autoencoder for Kaggle Dataset
An autoencoder implementation trained on a **custom Kaggle dataset** to compress and reconstruct image data.  
📄 [Autoencoder For kaggle data set.ipynb](https://github.com/Gulam-Kibria-GK/Image-Processing/blob/master/Autoencoder/Autoencoder%20For%20kaggle%20data%20set.ipynb)
💾 [model_500.h5](https://github.com/Gulam-Kibria-GK/Image-Processing/blob/master/Autoencoder/model_500.h5)

### 🔹 Autoencoder for Fashion-MNIST
This model is trained on the **Fashion MNIST** dataset to demonstrate basic encoder-decoder architecture for image reconstruction.  
📄 [Autoencoder_For_fashion_mnist_DataSet.ipynb](https://github.com/Gulam-Kibria-GK/Image-Processing/blob/master/Autoencoder/Autoencoder_For_fashion_mnist_DataSet.ipynb)  


## 🙋 Contact

=============================================== <br> 
Gulam Kibria Chowdhury <br>
CSE Graduate || Competitive Programmer <br>
Sylhet, Bangladesh <br>
Gmail: gkchowdhury101@gmail.com <br>
=============================================== <br>