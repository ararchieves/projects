# Autoencoders 

Autoencoder is an unsupervised artificial neural network that learns how to efficiently compress and encode data then learns how to reconstruct the data back fromthe reduced encoded representation toa representation that is as close to the original input as possible.

---

## Project: Mnist to 90deg

### Intorduction: 
The puspose of this project is to create a autencoder that takes input images of handwritten images and reconstuct 90&deg; version of the images. 

### Project Details

This project involves the following steps: 

- Downloading and loading `mnist` dataset from `torchvision` library. 
- Image visualization for input and desrired images. 
- Creating 3-layers CNN autoencoder model in pytorch. 
- Training the model on gpu for 10 epochs. 
- Evaluating the moddel and visualizing the learning of model. 

### Project objectives

The primary objective of this project is to get started with autoencoders and get a hands on experience and undersatnding with workings of a simple cnn autoencoder. 