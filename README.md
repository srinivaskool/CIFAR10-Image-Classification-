# CIFAR10-Image-Classification

Image classification on CIFAR-10 dataset using two models. First model is my own CNN(Convolutional neural network). The another model is built using Resnet-9 architecture.

<p align="center">
  <img  src="cifar10-resnet9\Capture.PNG" > 
</p>

---

### Table of Contents

- [Description](#description)
- [Datasets and Colab Links](#Datasets-and-Project-Colab-Links)
- [Results](#results)
- [Project Layout](#project-layout)
- [References](#references)
- [Author Info](#author-info)

---

## Description

### Built With

- PyTorch
- Matplotlib


### For Execution

The easiest way to start executing the code is to click the Run button at the top of this page and select Run on Colab. Google Colab is a free online platform for running Jupyter notebooks using Google's cloud infrastructure. You can also select "Run on Binder" or "Run on Kaggle" if you face issues running the notebook on Google Colab. 

To run the code on your computer locally, you'll need to set up Python, download the notebook and install the required libraries. We recommend using the Conda distribution of Python. Click the Run button at the top of this page, select the Run Locally option, and follow the instructions.
<br>

---

## Datasets and Project Colab Links

#### Dataset - [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html)
<br/>

<p align="center">
    <img src="README_IMAGES\3.png" > 
</p>

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.

### CIFAR-10 Image Classification using own CNN



[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1hpG1vH2bQBDpyyNkLk_0EWYryAlnTflw?usp=sharing)



### CIFAR10 Image Classification using Resnet-9 Architecture 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xFWyerR7-49Z-6lncSLfw_JJU8VUzhh5?usp=sharing)


---

## Results
<br>

### CIFAR-10 Image Classification using own CNN
<br>
- Accuracy achieved is <b> 76.03% </b>.
  <br/><br/>
<p align="center">
    <img  src="README_IMAGES\1.png" > 
</p>

<p align="center">
    <img  src="README_IMAGES\2.png" > 
</p>


<br>

### CIFAR10 Image Classification using Resnet-9 Architecture
<br>
- Accuracy achieved is <b> 92 % acuracy in just 4 min training</b>.
  <br/><br/>

<p align="center">
    <img  src="cifar10-resnet9\net.svg" > 
</p>

<p align="center">
    <img  src="README_IMAGES\4.png" > 
</p>

<p align="center">
    <img  src="README_IMAGES\5.png" > 
</p>

#### [Back To The Top](#CIFAR10-Image-Classification)

---

## Project Layout

```
CIFAR10-Image-Classification-CNN-and-ResNet
├─ Cifar-CNN
│  ├─ cifar10-cnn.pth
│  ├─ cifar10_cnn.ipynb
│  ├─ dataset.png
│  ├─ download (1).png
│  ├─ download (2).png
│  ├─ ep_res.PNG
│  └─ https_colab.docx
├─ cifar10-resnet9
│  ├─ Capture (1).PNG
│  ├─ Capture.PNG
│  ├─ cifar10-resnet9.pth
│  ├─ cifar10_ResNet9_architecture.ipynb
│  ├─ download (1).png
│  ├─ download (2).png
│  ├─ download.png
│  ├─ net.svg
│  ├─ RES.PNG
│  └─ Untitled document.docx
├─ README.md
└─ README_IMAGES
   ├─ 1.png
   ├─ 2.png
   ├─ 3.png
   ├─ 4.png
   └─ 5.png

```
---

## References

- [PyTorch](https://pytorch.org/)
- [Matplotlib](https://matplotlib.org/)

---

## Author Info

- LinkedIn - [Srinivas K](https://www.linkedin.com/in/srinivas-konduri/)
- Github - [Srinivas K](https://github.com/srinivaskool)
- Portfolio - [Srinivas K](http://srinivask.me/portfolio)

#### [Back To The Top](#CIFAR10-Image-Classification)


