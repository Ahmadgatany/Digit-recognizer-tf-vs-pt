# PyTorch vs TensorFlow: Digit Recognizer Comparison

This project presents a comparison between **PyTorch** and **TensorFlow** implementations for digit recognition using the **MNIST dataset**. The project includes model building and evaluation for **classifying handwritten digits (0-9)**.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model Implementations](#model-implementations)
- [Requirements](#requirements)
- [Usage](#usage)
- [Training Results](#training-results)
- [Evaluation](#evaluation)
- [Submission](#submission)
- [Links](#links)
- [License](#license)

## Overview
This project compares the two most popular deep learning frameworks:
- **TensorFlow**: Known for its flexibility and ease of use for both beginners and experts.
- **PyTorch**: Preferred by researchers for its dynamic computational graphs and intuitive API.

Each framework is used to build Convolutional Neural Networks (CNNs) to recognize handwritten digits.

## Dataset
The dataset used for training and testing is the **MNIST dataset** from Kaggle. This dataset contains grayscale images of handwritten digits (0-9), and each image is of size 28x28 pixels.

You can access the dataset from [Kaggle's Digit Recognizer Competition](https://www.kaggle.com/competitions/digit-recognizer).

## Model Implementations
- **TensorFlow Implementation**: A CNN model was built using TensorFlow and Keras to classify the images.
- **PyTorch Implementation**: The same architecture was implemented using PyTorch to provide a direct comparison.

## Requirements
To run the project, you need the following libraries:
- **Python 3.8+**
- **TensorFlow 2.0+**
- **PyTorch 1.6+**
- **NumPy**
- **Matplotlib**
- **Pandas**
  
You can install the required libraries using:

```bash
pip install -r requirements.txt
