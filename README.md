# DCGAN_LSGAN_WGAN_WGAN-GP_SNGAN_RSGAN_RaSGAN_BEGAN
Implementation of some different variants of GANs 

## Introduction
--------------

This code is mainly implement some basic GANs about 'DCGAN', 'WGAN', 'WGAN-GP', 'LSGAN', 'SNGAN', 'RSGAN'&'RaSGAN', 'BEGAN'. 

More details of these GANs, please see follow papers:

1. DCGAN: [Unsupervised representation learning with deep convolutional generative adversarial networks](https://arxiv.org/pdf/1511.06434.pdf%C3%AF%C2%BC%E2%80%B0)

2. WGAN: [Wasserstein gan](https://arxiv.org/pdf/1701.07875.pdf?__hstc=200028081.1bb630f9cde2cb5f07430159d50a3c91.1524009600081.1524009600082.1524009600083.1&__hssc=200028081.1.1524009600084&__hsfp=1773666937)

3. WGAN-GP: [Improved training of wasserstein gans](https://papers.nips.cc/paper/7159-improved-training-of-wasserstein-gans.pdf)

4. LSGAN: [Least Squares Generative Adversarial Networks](http://openaccess.thecvf.com/content_ICCV_2017/papers/Mao_Least_Squares_Generative_ICCV_2017_paper.pdf)

5. SNGAN: [Spectral normalization for generative adversarial networks](https://arxiv.org/pdf/1802.05957.pdf)

6. RSGAN&RaSGAN: [The relativistic discriminator: a key element missing from standard GAN](https://arxiv.org/abs/1807.00734)

7. BEGAN:[BEGAN: Boundary Equilibrium Generative Adversarial Networks](https://arxiv.org/pdf/1703.10717.pdf)
## Attention
If your computer don't have GPU to accelerate the training process, please click [Google Cloud Colab](https://colab.research.google.com/drive/1BKGcw58kOQc4mxxm4VbAJ6BX-DEzZtgE) to train the GANs.
## How to use 
Firstly, you should download the data 'facedata.mat' from [Baidu Drive](https://pan.baidu.com/s/12fcKytGOW222bS5BccteYw) or [Google Drive](https://drive.google.com/open?id=1ROGET9rA5WAdU3C8Lfs5mxg5ufLD2uCO), then put the file 'facedata.mat' into the folder 'TrainingSet'.

## Requirements
1. python3.5
2. tensorflow1.4.0
3. pillow
4. scipy
5. numpy

Results of this code
--------------------
This result is using DCGAN trained about 8000 iterations.
<div align=center><img src="https://github.com/MingtaoGuo/DCGAN_LSGAN_WGAN_WGAN-GP_SNGAN/raw/master/Image/DCGAN.jpg"/></div>

Compare LSGAN, WGAN, WGAN-GP, SNGAN, RSGAN of different iteration
-----------------------------------------------------
![](https://github.com/MingtaoGuo/DCGAN_LSGAN_WGAN_WGAN-GP_SNGAN/raw/master/Image/GAN.jpg)

Convergence of BEGAN
------------------------
![](https://github.com/MingtaoGuo/DCGAN_LSGAN_WGAN_WGAN-GP_SNGAN/raw/master/Image/BEGAN.jpg)
![](https://github.com/MingtaoGuo/DCGAN_LSGAN_WGAN_WGAN-GP_SNGAN/raw/master/Image/BEGAN_converge.jpg)
