# Digit-recognition
# Handwritten Digit Recognition with Convolutional Neural Network

This project implements a machine learning model to recognize handwritten digits (0-9) using the famous MNIST dataset. The model is built using a Convolutional Neural Network (CNN) implemented with TensorFlow and Keras.

## Table of Contents
1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Usage](#usage)
   

## Introduction
Handwritten digit recognition is a fundamental problem in the field of computer vision and machine learning. The MNIST dataset consists of 28x28 grayscale images of handwritten digits along with their corresponding labels (0 to 9). The goal of this project is to build a CNN model that can accurately classify these digits.

## Requirements
To run this project, you need the following dependencies:
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib

Installation
Clone this repository to your local machine or download the source code as a ZIP file.
Make sure you have all the required dependencies installed (see Requirements).
Open a terminal or command prompt and navigate to the project directory.
Usage
The main script for the project is digit_recognition.py.
The script will load the MNIST dataset, preprocess the data, build and train the CNN model, and then evaluate its performance on the test set.
After training, the script will display the test accuracy of the model and show predictions for the first ten test images along with their actual labels.
Results
The model's accuracy on the test set will be displayed in the terminal after training. Additionally, the script will show sample images from the test set and their corresponding predicted labels using matplotlib.





