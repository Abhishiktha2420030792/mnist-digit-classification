# Handwritten Digit Recognition Using Deep Learning

## Project Overview

This project implements a Deep Learning model to classify handwritten digits (0–9) using the MNIST dataset. The model is built using TensorFlow and Keras and trained on 60,000 handwritten digit images.

## Objective

To develop an image classification system capable of accurately recognizing handwritten digits using a neural network.

## Dataset

The MNIST dataset consists of:

* 60,000 training images
* 10,000 testing images
* 10 digit classes (0–9)
* Image size: 28 × 28 pixels

## Technologies Used

* Python
* Google Colab
* TensorFlow
* Keras
* NumPy
* Matplotlib

## Model Architecture

* Flatten Layer
* Dense Layer (128 neurons, ReLU activation)
* Dense Layer (64 neurons, ReLU activation)
* Output Layer (10 neurons, Softmax activation)

## Project Workflow

1. Import required libraries
2. Load MNIST dataset
3. Visualize sample images
4. Normalize image pixel values
5. Build neural network model
6. Train the model
7. Evaluate performance
8. Make predictions
9. Save the trained model

## Results

* Test Accuracy: **97.58%**
* Successfully classified handwritten digits from 0–9.

## Files in Repository

* `MNIST_Image_Classification.ipynb` – Complete project notebook
* `mnist_model.keras` – Trained deep learning model
* `README.md` – Project documentation

## Conclusion

The neural network achieved high accuracy on the MNIST dataset, demonstrating the effectiveness of deep learning techniques for image classification tasks.

## Future Improvements

* Implement Convolutional Neural Networks (CNNs)
* Deploy as a web application using Streamlit
* Add support for custom handwritten digit images
