# Traffic-Sign-Detection

This project develops a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify traffic signs from the German Traffic Sign Recognition Benchmark (GTSRB) dataset. The model is designed to accurately identify 43 different traffic signs and is optimized through several stages of data preprocessing, model tuning, and augmentation strategies.

## Features

- Data Preprocessing: Includes grayscale conversion, normalization, and histogram equalization to improve model training efficiency.
- Model Architecture: Utilizes a multi-layer CNN for feature extraction and classification.
- Training: Implements various techniques such as dropout, data augmentation, and hyperparameter tuning to enhance model performance.
- Evaluation: Assesses model accuracy and generalization on unseen data using a split of training and test datasets.

## Prerequisites

Before you can run this project, you'll need to install the following software: \
Python 3.x \
Jupyter Notebook \
TensorFlow 2.x \
Keras \
NumPy \
Matplotlib \
OpenCV (for image preprocessing)

## Model Architecture

Utilized the LeNet architecture, a multi-layer Convolutional Neural Network, for effective feature extraction and classification of traffic signs. Adaptations and enhancements were applied to the standard LeNet model to optimize performance for traffic sign recognition.

## Results

Initial model accuracy: 91.38% \
After optimizations: 95.58% \
Post data augmentation: 95.73% \
Final model accuracy: 96.88%

These results demonstrate the effectiveness of the model in classifying traffic signs with high accuracy.
