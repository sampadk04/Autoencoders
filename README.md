# Autoencoders

## Implementation of AutoEncoders from scratch using PyTorch

We implemented 3 types of AutoEncoders on the MNIST handwritten digits dataset:
- Simple AutoEncoder
- De-Noising AutoEncoder
- Variational AutoEncoder

Implementation of Variational AutoEncoder has been inspired from the original AutoEncoder paper names "[Auto-Encoding Variational Bayes](https://arxiv.org/abs/1312.6114v10)".

Here are some demonstration from the codes:

- Reconstruction of Simple AutoEncoder:
![](sample_images/SAE_reconstruction.jpeg)

- Reconstruction of De-Noising AutoEncoder:
![](sample_images/DAE_reconstruction.jpeg)

- Interpolation by Variational AutoEncoder:
![](sample_images/VAE_interpolation.jpeg)