# Handwritten Character Recognition

CodeAlpha Machine Learning Internship - Task 3

## Objective
Identify handwritten digits (0-9) from images using deep learning.

## Dataset
MNIST handwritten digits dataset (60,000 training and 10,000 test images, 28x28 grayscale).

## Approach
- Normalized pixel values (0-1) and reshaped images
- One-hot encoded labels
- Built a Convolutional Neural Network (CNN):
  2 Conv2D + MaxPooling layers, Dense layer, Dropout (0.3), Softmax output
- Trained for 5 epochs (Adam optimizer)
- Evaluated with accuracy, precision, recall and F1-score

## Results
Test Accuracy: 99.02%
Precision, Recall and F1-score: 0.99 (macro average)

## Tools
Python, TensorFlow/Keras, NumPy, Matplotlib, Scikit-learn, Google Colab
