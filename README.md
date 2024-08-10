# Fashion MNIST Autoencoder

## Overview

This project implements an Autoencoder using the Fashion MNIST dataset. The Autoencoder is trained to compress (encode) and then reconstruct (decode) images from the dataset. Additionally, it is tested on its ability to remove noise from images, showcasing its potential as a denoising autoencoder.

## Dataset

The [Fashion MNIST dataset](https://github.com/zalandoresearch/fashion-mnist) is a collection of 70,000 grayscale images in 10 categories, with 7,000 images per category. The images show individual articles of clothing at low resolution (28x28 pixels), as seen below:

**Sample Images from the Fashion MNIST Dataset**

![Fashion MNIST Sample](<path_to_your_image>) 

## Features

- **Autoencoder Architecture**: The model is a symmetric neural network with encoding and decoding layers.
- **Denoising Capability**: The Autoencoder is tested on noisy images to evaluate its performance in reconstructing the original images.
- **Visualization**: The project includes code to visualize the original, noisy, and reconstructed images.

## Results :

![download](https://github.com/user-attachments/assets/eaa7ebde-9931-4cd7-8bbb-4865b43ad89d)
