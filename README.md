
# Comparative Analysis of Pretrained Models for Alzheimer’s Disease Classification

## Overview

This project focuses on the classification of Alzheimer's Disease (AD) using MRI images. The objective is to develop and compare pre-trained deep learning models that can accurately classify MRI images into different stages of Alzheimer's Disease.

## Datasets

Two distinct datasets were utilized in this study, each contributing to the comprehensive analysis of Alzheimer's disease classification. Both datasets were sourced from Kaggle, providing a rich and diverse collection of brain MRI images for our study.

### 1. Augmented Alzheimer MRI Dataset
The "Augmented Alzheimer MRI Dataset" comprises a total of 33,984 images, meticulously categorized into four distinct classes:
- **Non-Demented**
- **Mildly Demented**
- **Very Mildly Demented**
- **Moderate Demented**

This dataset was used extensively for training and validating the models. The augmentation of images ensures a diverse set of examples, helping the models generalize better across different cases of Alzheimer’s disease.

### 2. Alzheimer's Dataset 4 Class of Images
The second dataset, "Alzheimer's Dataset 4 Class of Images," is organized into two primary folders: **train** and **test**. This dataset consists of a total of 6,400 images, with the "test" folder containing 1,279 images. The images are distributed across the following four predefined categories:
- **Non-Demented**
- **Mildly Demented**
- **Very Mildly Demented**
- **Moderate Demented**

This dataset was crucial for evaluating the model's performance and ensuring the accuracy of the classification across the different stages of Alzheimer’s disease.

## Model Architectures

Two pretrained models were utilized in this study for Alzheimer's Disease classification:

### 1. DenseNet169
   - **Description**: DenseNet169 is a convolutional neural network that connects each layer to every other layer in a feed-forward fashion. This dense connectivity pattern helps the model learn complex patterns in the data.
   - **Performance**: The model performed reasonably well but was outperformed by the Inception V3 model in terms of accuracy.

### 2. Inception V3
   - **Description**: Inception V3 is a highly efficient convolutional neural network known for its computational efficiency and accuracy. It uses factorized convolutions and aggressive regularization, which help in achieving better performance.
   - **Performance**: Inception V3 achieved a superior accuracy of **93.59%**, outperforming DenseNet169, making it the preferred model for Alzheimer’s disease classification based on the datasets used in this study.

## Results

The following table summarizes the performance of the two models:

| **Model**      | **Training Accuracy** | **Testing Accuracy** | **Images Predicted Correctly** |
|----------------|-----------------------|----------------------|--------------------------------|
| **InceptionV3**| 92.27%                | 93.59%               | 1190/1279                      |
| **DenseNet169**| 91.79%                | 77.24%               | 987/1279                       |

## Read the Research Paper

For a detailed explanation of the methods, experiments, and results, you can read the full research paper [here](https://docs.google.com/document/d/1FIKYjrFpg56P8tm0cEb4tK3DOruB9OkI_3QBp6a5QYc/edit?usp=sharing). 

