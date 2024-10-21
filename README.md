Digit Recognizer: PyTorch vs TensorFlow
This project compares two popular deep learning frameworks, PyTorch and TensorFlow, in a classic image classification problem: the Digit Recognizer competition on Kaggle.

Overview
In this notebook, I implement the same Convolutional Neural Network (CNN) architecture using both PyTorch and TensorFlow to classify handwritten digits (0-9) from the MNIST dataset. The key steps include:

Data Loading and Preprocessing: Normalize and reshape the input images.
Model Building: Construct CNNs in both frameworks.
Training: Train the models and compare their performance on validation data.
Evaluation: Validate and predict the test set, followed by submission generation for Kaggle.
This notebook will help you understand how each framework handles common deep learning tasks like model definition, training, and evaluation.

Notebook Link
You can view and run the notebook on Kaggle using the following link:
[Digit Recognizer: PyTorch vs TensorFlow
](https://www.kaggle.com/code/ahmedgaitani/digit-recognizer-code-dl-tf-vs-pt-99)
Dataset
The dataset used in this project is the Digit Recognizer dataset available on Kaggle. It consists of 42,000 grayscale images of handwritten digits for training and 28,000 images for testing.

Access the dataset here:
[Digit Recognizer Dataset on Kaggle](https://www.kaggle.com/competitions/digit-recognizer)

Table of Contents
Imports: Loading the necessary libraries for both frameworks.
Data Loading and Preprocessing: Loading and preparing the dataset.
Model Definition: Constructing the CNN models using TensorFlow and PyTorch.
Training: Training the models on the training dataset.
Evaluation: Evaluating the models on the validation dataset.
Prediction and Submission: Making predictions on the test set and preparing the submission files.
Requirements
To run this notebook, you need the following libraries:

TensorFlow
PyTorch
Numpy
Pandas
Scikit-learn
Matplotlib (optional, for visualizing results)
