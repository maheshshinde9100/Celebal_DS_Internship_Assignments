# Week 4 Assignment - CIFAR-10 Image Classification (ANN vs CNN)

## Overview

This assignment implements image classification on the CIFAR-10 dataset using Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN). The performance of both models is compared, and techniques such as Early Stopping and Data Augmentation are applied to improve the CNN model.

## Tasks Completed

- Loaded the CIFAR-10 dataset
- Preprocessed the data (normalization and flattening for ANN)
- Built and trained an ANN model
- Built and trained a CNN model
- Evaluated both models on the test dataset
- Compared training and validation accuracy/loss
- Applied Early Stopping to reduce overfitting
- Applied Data Augmentation to improve generalization
- Compared ANN and CNN performance

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib

## Dataset

- CIFAR-10
- 60,000 RGB images
- 10 image classes
- 50,000 training images
- 10,000 testing images

## Conclusion

The CNN model achieved better performance than the ANN by effectively learning spatial features from images. Early Stopping and Data Augmentation further improved the model's generalization.
```
