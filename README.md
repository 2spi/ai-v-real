# Real vs AI Generated Image Classifier

This repository contains the code and resources for a machine learning project that aims to classify images as either real or AI-generated using Convolutional Neural Networks (CNNs).

## Project Overview

The Real vs AI Generated Image Classifier project utilizes CNNs to accurately distinguish between real and AI-generated images. The model was built using TensorFlow's Keras API.

## Model Performance

The trained image classification model achieved the following performance metrics:

- **Precision**: 0.928085
- **Recall**: 0.896496
- **Accuracy**: 0.913238

These metrics indicate that the model exhibits high precision and recall, with an overall accuracy of 91.32% in classifying real and AI-generated images.

## Dataset

The dataset used for training and evaluation consists of two categories of images:

- **REAL images**: These images are sourced from the Krizhevsky & Hinton's CIFAR-10 dataset, which is a widely-used benchmark dataset for image classification tasks.
- **FAKE images**: These images were generated using the equivalent of CIFAR-10 with Stable Diffusion version 1.4.

The combined dataset provides a diverse set of real and AI-generated images for training the classification model.

### References
Krizhevsky, A., & Hinton, G. (2009). Learning multiple layers of features from tiny images.

Bird, J.J., Lotfi, A. (2023). CIFAKE: Image Classification and Explainable Identification of AI-Generated Synthetic Images. arXiv preprint arXiv:2303.14126.

Real images are from Krizhevsky & Hinton (2009), fake images are from Bird & Lotfi (2023).
