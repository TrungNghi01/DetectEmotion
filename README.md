# Real-Time Facial Expression Recognition using CNNs

This project demonstrates how Convolutional Neural Networks (CNNs) can be used to recognize facial expressions and classify them into emotional categories. All code was developed and tested in a Jupyter Notebook environment running on Anaconda.

## Project Overview

Facial Expression Recognition (FER) is a crucial application in computer vision where the goal is to identify human emotions like happiness, sadness, surprise, anger, and more using facial expressions. This project implements a CNN model to classify facial expressions based on images.

## Why CNNs?

CNNs are ideal for image classification tasks because they can automatically extract spatial features such as edges, patterns, and shapes directly from pixel data. Their layered architecture allows them to learn hierarchical image features, which is essential for recognizing subtle facial expressions.

## Libraries Used

PyTorch

Torchvision

NumPy

Matplotlib

Pandas

To install the required packages:
```bash
pip install torch torchvision
pip install numpy pandas matplotlib
```
# Dataset

We use the FER2013 Dataset, which includes thousands of grayscale images labeled with seven emotion categories:

Happy

Sad

Angry

Surprise

Disgust

Fear

Neutral

Dataset link: https://www.kaggle.com/datasets/msambare/fer2013

Each image is provided in CSV format with pixel values and corresponding emotion labels.

# Environment

This project is developed and run in:

Anaconda Distribution

Jupyter Notebook interface

# Conclusion

The CNN model achieved good performance on classifying facial expressions. Future improvements could include using pre-trained models, deeper CNN architectures, or data augmentation to enhance model robustness. This work demonstrates the effectiveness of CNNs in real-world scenarios like healthcare, customer feedback, or human-robot interaction.

