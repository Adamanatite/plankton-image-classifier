# CNN for Plankton Type Classification
A deep CNN for classifying types of plankton from a small (n=1,617) multiclass (12 class) dataset of low-resolution plankton images. This was completed as a piece of 4th year university coursework.

The Jupyter notebook contains:
* Code for data loading with image normalisation
* Data augmentation using random rotation and cropping to increase dataset size and balance classes
* An implementation of a CNN architecture to classify the types of plankton in the images
* Model architecture changes and hyperparameter optimisation (using K-fold cross-validation)
