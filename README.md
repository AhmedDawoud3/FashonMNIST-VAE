# FashonMNIST-VAE
This repository contains an implementation of a Variational Autoencoder (VAE) trained on the FashionMNIST dataset. The dataset is augmented with a colorization step to enhance visualization, helping to better interpret the learned latent representations.

## Features
- **Encoder**: Maps input images to a lower-dimensional latent space.
- **Reparameterization** Trick: Ensures smooth and differentiable sampling from the latent space.
- **Decoder**: Reconstructs images from the learned latent representation.
- **Colorized FashionMNIST**: Enhances grayscale images by assigning colors based on class labels.


![Training](https://github.com/user-attachments/assets/d2881fc2-2c18-45c1-b8ce-46779c77a549)

![gen](https://github.com/user-attachments/assets/0b99844f-73ea-417a-a0ff-cc360158dfba)


This implementation is based on the Variational Autoencoder framework. For more details, see the original paper: [Auto-Encoding Variational Bayes by Kingma and Welling.](https://arxiv.org/abs/1312.6114)
