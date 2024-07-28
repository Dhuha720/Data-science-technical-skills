# Classify Facial Expressions

This project aims to classify facial expressions using convolutional neural networks (CNNs) with TensorFlow/Keras, and pretrained models like VGG and ResNet.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Results](#results)

## Overview
This project classifies facial expressions from images using deep learning techniques. The model is trained to recognize six different expressions: happy, sad, angry, surprised, neutral, and fearful.

## Dataset
The dataset used for this project is from Kaggle and consists of images labeled with different facial expressions. You can find the dataset here: [Facial Expression Dataset](https://www.kaggle.com/datasets/aadityasinghal/facial-expression-dataset).

## Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
    
## Model Architecture
The model is built using the Sequential API from Keras with the following layers:
- 4 Convolutional layers with Batch Normalization, ReLU activation, and Max Pooling
- Flatten layer
- 2 Dense layers with Batch Normalization, ReLU activation, and Dropout
- Output layer with Softmax activation

## Results
- Model from Scratch
- VGG16 Model 
- ResNet50 Model
