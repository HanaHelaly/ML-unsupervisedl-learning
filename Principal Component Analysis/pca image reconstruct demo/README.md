# PCA Image Reconstruction Demo

- This project demonstrates the effect of different numbers of components in Principal Component Analysis (PCA) on the resolution of images. 
- PCA is used to reduce the dimensionality of image data and reconstruct images from a lower-dimensional representation.

## Overview

- Principal Component Analysis (PCA) is a dimensionality reduction technique commonly used in image processing and computer vision. By projecting high-dimensional data onto a lower-dimensional subspace, PCA can capture the most important features of the data while reducing its complexity.

- In this code, we apply PCA to a dataset of faces dataset and observe how the number of components affects the resolution of the reconstructed images. We use the famous Olivetti faces dataset, which contains grayscale images of human faces.


## Results

- The .ipynb `pca_image_reconstruction.ipynb` contains the code for loading the dataset (faces in scikit-learn), applying PCA, and reconstructing images. It utilizes the scikit-learn library for PCA.

- The key observation from the results is that as the number of PCA components increases, the resolution and quality of the reconstructed images improve. However, there is a trade-off between image quality and the dimensionality of the data.
