# Variational Autoencoder Project

## Overview
This project implements a variational autoencoder (VAE) using TensorFlow and demonstrates its functionality through interactive graphical user interfaces (GUI) in Jupyter Notebooks. The VAE is trained on the FER2013 dataset for facial expression recognition.

## Files
- **Mohammed_01.ipynb**: Jupyter Notebook for GUI display and interaction. This notebook directly calls the saved trained models to run.
- **Mohammed_02.ipynb**: Jupyter Notebook for complete model training and GUI output. This notebook includes code for model training, saving the models, and GUI interaction.

## Dependencies
Ensure you have the following dependencies installed in your environment:
- numpy==1.20.0
- tensorflow==2.8.0
- ipywidgets==7.6.5
- Pillow==8.2.0

## Instructions
1. Run VAE_01.ipynb to interact with the GUI. This notebook directly calls the saved trained models to display the results.
2. If encountering any errors while interacting with the GUI in VAE_01.ipynb, rerun Cell 3.
3. For Task two, upload an image from the FER2013 dataset in VAE_02.ipynb and interact with the reconstructed images from both models.

## Dataset
The models have been trained on the FER2013 dataset, which contains facial images with labeled emotions.

## Notes
- The provided code includes functions for mean squared error (MSE) calculation, structural similarity index (SSIM), and peak signal-to-noise ratio (PSNR) calculation.
- Trained models are stored in the VAE folder.
- Ensure to adjust file paths in the code according to your system configuration.
