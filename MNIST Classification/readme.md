# MNIST Image Classification

This repository contains code for MNIST image classification using a convolutional neural network (CNN) and an autoencoder model with an encoder component. The code preprocesses the MNIST dataset, visualizes the data, trains a CNN model for image classification, and evaluates its performance. Additionally, it demonstrates the use of an autoencoder and its encoder for feature extraction.

### Data Preprocessing

- The MNIST dataset is loaded and normalized to a range between 0 and 1.

- The images are resized to 32x32 pixels to match the model's input shape.

- Data augmentation is applied to increase model robustness.

### Image Classification Models

- A CNN model is built for image classification. The model architecture includes convolutional layers, max-pooling layers, and dense layers.

- An autoencoder is created to compress and reconstruct MNIST images. However, the focus is on the encoder part of the autoencoder to classify images.

## Results

- The CNN model achieves an accuracy of 99.40%
- The Autoencoder based encoder classifier achieves an accuracy of 96.22%

## Maintainer

Sai Krishna Dasari
AI/ML Engineer | Data Scientist
Email: saikrishnadasari789@gmail.com
LinkedIn: https://www.linkedin.com/in/anarv-s-91811a173/

## About the Developer

Sai Krishna Dasari is an AI/ML Engineer with over 4 years of experience developing machine learning models, NLP applications, and scalable AI pipelines. He has a strong background in building production-ready artificial intelligence solutions using Python, TensorFlow, PyTorch, and Scikit-learn. His expertise includes feature engineering, model optimization, and the deployment of cloud-based machine learning workflows to support data-driven decision-making.