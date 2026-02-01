# Image Colorization and Segmentation

This repository contains implementations of two major computer vision tasks using PyTorch:
1.  **Image Colorization** using a Variational Autoencoder (VAE).
2.  **Image Segmentation** using the U-Net architecture.

## Overview

### Image Colorization (VAE)
The goal of this part is to colorize grayscale images. A Variational Autoencoder (VAE) is trained to map grayscale input images to their color distribution in the latent space and reconstruct the colored image.

### Image Segmentation (U-Net)
This part focuses on semantic image segmentation. The U-Net architecture, known for its effectiveness in biomedical image segmentation, is implemented and trained to classify each pixel of an image into a corresponding class.

## Key Features
- **VAE Implementation**: Custom encoder and decoder networks with reparameterization trick.
- **U-Net Architecture**: Full implementation of the U-Net model with contracting and expansive paths.
- **Custom Datasets**: Data loading and preprocessing pipelines for both tasks.
- **Training Loops**: Complete training, validation, and testing loops with loss visualization.

## Dependencies
- Python 3.12
- PyTorch
- NumPy
- Matplotlib
- PIL (Python Imaging Library)
- ipywidgets (for progress bars)

## Usage
Open the notebook `Image_Colorization_and_Segmentation_VAE_UNet.ipynb` in Jupyter Notebook or Google Colab to run the code. Ensure the datasets are placed in the correct directories as expected by the data loaders.
