# CosmosVAE
Variational Autoencoder for Cosmos-Web data to understand where Little Red Dots (LRD) lie in the Latent Space 

A link to a subset of the data we plan to use is https://drive.google.com/drive/folders/1oQAhH3gSEgdD4I8O4NnXUke1aPb0D3Yl?usp=sharing 

## Data generator

This file is used to take data downloaded from the Cosmos dataset website to create datasets of image cutouts, redshifts, and labels for objects within similar redshift of the LRDs.

## VAE Implementation

This file is used to train and test the VAE with the datasets created from the previous file. By default, it uses the subset of the data as linked above.

Ensure that `TensorFlow` is installed correctly on your device prior to running the notebook. See the TensorFlow installation documentation here: https://www.tensorflow.org/install/pip

## Test model

This file loads a pre-trained version of the model built in the previous file so that it can be tested on reconstructing the images and redshifts, as well as visualizing the latent space.
