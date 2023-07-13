# Landscape Colourization with Autoencoders

## Introduction:
This project aims to explore the capabilities of autoencoders, which are neural networks that can compress and reconstruct data. By using autoencoders to generate the colors of a landscape, we can learn how they map the data into a lower-dimensional latent space and how they recover the original features from that space. We also investigate the role of skip layers (RESNET), which connect the encoder and decoder parts of the network and allow them to leverage the encoded information more effectively.

## Dataset

The dataset used for this project consists of around 7k grayscale and color images of the same area. Images are of size `150x150`. The dataset is open source on kaggle with this [link](https://www.kaggle.com/datasets/theblackmamba31/landscape-image-colorization).