# Machine Learning with Python - Cats vs Dogs Image Classification

This project is part of the **Machine Learning with Python Certification** offered by freeCodeCamp. The objective of the project is to create a Convolutional Neural Network (CNN) model that classifies images of cats and dogs using TensorFlow 2.0 and Keras. The model is trained to identify and classify the images with at least 63% accuracy.

## Project Overview

In this project, we:

- Build a Convolutional Neural Network (CNN) using TensorFlow and Keras.
- Preprocess and augment image data to enhance model performance.
- Train and validate the model on a dataset of labeled images of cats and dogs.
- Evaluate the model’s accuracy on a test dataset.

The project involves:

- Loading the dataset and performing basic data preprocessing.
- Applying data augmentation techniques to improve model generalization.
- Building the CNN model architecture and compiling it.
- Training the model and evaluating its performance.
- Visualizing results with training/validation accuracy and loss.

## Dataset

The dataset used in this project is a collection of images of cats and dogs. The data has been split into the following directories:

- `train/` — Contains images used for training the model, divided into subdirectories for cats and dogs.
- `validation/` — Contains images used for validating the model’s performance during training.
- `test/` — Contains images used for testing the model's final performance.

The dataset was originally sourced from [freeCodeCamp](https://www.freecodecamp.org/), and you can access the full dataset via the course.

## Requirements

- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- Pandas
- OS (for file handling)
