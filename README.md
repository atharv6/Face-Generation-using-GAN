### Face Generation Using Deep Convoutional Generative Adversarial Netwroks (DCGAN)

## Overview

In this project, I built two neural network compete against each other to generate new faces image from CelebA which is a large-scale face attributes dataset with more than 200K celebrity images.

# Generative Adversarial Networks (GAN)
Generative adversarial networks (GAN's) are algorithmic architectures that use two neural networks, pitting one against the other (thus the “adversarial”) in order to generate new, synthetic instances of data that can pass for real data. They are used widely in image generation, video generation and voice generation.

# Deep Convolutional Generative Adversarial Networks (DCGAN)
A DCGAN is a extension of the GAN, except that it explicitly uses convolutionallayers in the discriminator and convolutional-transpose layers in generator, respectively. It was first described by **Radford et. al.** in the paper **Unsupervised Representation Learning With Deep Convolutional Generative Adversarial Networks**. It uses convolutional stride and transposed convolution for the downsampling and the upsampling.

# Setup
This project requires GPU acceleration to run efficiently. Support is available to use either of the following two methods for accessing GPU-enabled cloud computing resources.

# Dataset
I used the CelebFaces Attributes Dataset (CelebA) to train the adversarial networks.
