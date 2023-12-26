# Variational Autoencoders

## Introduction

This GitHub repository contains a Jupyter notebook focused on implementing and exploring Variational Autoencoders (VAE). The primary objective is to train a VAE on the MNIST dataset, utilizing the latent representation for generating new samples, performing interpolations between two samples, and investigating the impact of hyperparameters on the quality of the learned latent representation.

## Requirements
Ensure you have the following dependencies installed:
- [PyTorch](https://pytorch.org/)
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [tqdm](https://github.com/tqdm/tqdm)
- [torchvision](https://pytorch.org/vision/stable/index.html)

You can install the dependencies using the following command:
```bash
pip install torch numpy matplotlib tqdm torchvision
```

## Notebook Structure
The notebook is organized into the following sections:

1. **Autoencoder Implementation**: Implementing an Autoencoder (AE) as a baseline model for learning the latent representation of the MNIST dataset.
   
2. **Variational Autoencoder (VAE) Implementation**: Implementing a Variational Autoencoder and training it on the MNIST dataset.
   
3. **Latent Representation Visualization**: Visualizing the learned latent representation by sampling from the prior and interpolating between two samples.
   
4. **Hyperparameter Exploration**: Exploring the effect of the VAE's hyperparameters on the quality of the learned latent representation.
   
5. **Conditional VAE (CVAE) Implementation**: Implementing a Conditional Variational Autoencoder (CVAE) and training it on the MNIST dataset.
   
6. **CVAE Latent Representation Visualization**: Visualizing the learned latent representation of the CVAE by sampling from the prior and interpolating between two samples.
   
7. **CVAE Hyperparameter Exploration**: Exploring the effect of the CVAE's hyperparameters on the quality of the learned latent representation.

## Acknowledgement
This project is part of an assignment for CSCI 566 at the University of Southern California in Spring 2023, under the guidance of Professor Jesse Thomason. Special thanks to the course producers for their contributions.

## How to Use
Simply open the Jupyter notebook and follow the step-by-step instructions and code cells to understand the implementation details and experiment with different configurations.

Feel free to contribute, report issues, or suggest improvements!

**Note**: It is recommended to run the notebook in an environment with GPU support for faster training.

Enjoy exploring Variational Autoencoders!