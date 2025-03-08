# Potato Disease Detection using Deep Learning

## Overview

Farmers who grow potatoes face significant economic losses due to diseases affecting potato plants. Two of the most common diseases are:

- **Early Blight** (caused by a fungus)
- **Late Blight** (caused by a microorganism)

Timely detection of these diseases can help farmers take appropriate actions and prevent crop losses. **AtliQ Agriculture**, an AI company, has taken the initiative to develop a mobile application that allows farmers to detect these diseases by simply capturing an image of the potato plant. The app utilizes **Deep Learning and Convolutional Neural Networks (CNN)** to classify the plant as:

- **Healthy**
- **Early Blight Infected**
- **Late Blight Infected**

## Features

1. Identify whether the potato plant is healthy or diseased  
2. Detect **Early Blight** and **Late Blight**  
3. Uses **Convolutional Neural Networks (CNN)** for classification  
4. Built for mobile integration  
5.Helps in reducing economic losses for farmers  

## Dataset

The dataset used for training the model consists of images of **healthy**, **early blight**, and **late blight** potato plants. It has been collected from various agricultural sources and processed for training. The dataset is taken from Kaggle through this [link](https://www.kaggle.com/datasets/arjuntejaswi/plant-village).

## Model Architecture

The model is built using **TensorFlow/Keras** and follows a CNN-based approach:

1. **Preprocessing**: Image resizing and normalization  
2. **Data Augmentation**: Random flipping, rotation to improve generalization  
3. **CNN Layers**:
    - Convolutional layers with ReLU activation  
    - MaxPooling layers for feature extraction  
    - Fully connected (Dense) layers for classification  
4. **Softmax Output Layer**: Outputs probabilities for the three classes  

## Training & Performance

- **Optimizer**: Adam  
- **Loss Function**: Sparse Categorical Crossentropy  
- **Evaluation Metric**: Accuracy  
- **Training done using Google Colab**

