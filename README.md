# Handwritten Digit Recognition Using CNN

## Project Overview

This project uses a **Convolutional Neural Network (CNN)** to recognize handwritten digits from images.

The images were collected for digits **0–9** and processed before training the CNN model.

## Dataset

The dataset contains handwritten digit images organized into folders from `0` to `9`.

Image counts:

* 0: 100
* 1: 109
* 2: 118
* 3: 100
* 4: 87
* 5: 80
* 6: 96
* 7: 56
* 8: 100
* 9: 100

## Image Preprocessing

The images were processed using several steps:

* Image quality checking
* Cropping
* Grayscale conversion
* Lighting and background normalization
* Centering the digit
* Resizing to **32 × 32**
* Pixel normalization
* Training/validation/test splitting
* Data augmentation on the training data

## Model

A small **Convolutional Neural Network (CNN)** was developed to classify the images into the 10 digit classes.

The model learns visual patterns such as edges, shapes, and digit structures to make predictions.

## Technologies

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Project Structure


handwritten-digit-recognition-cnn/
│
├── notebooks/
│   └── handwritten_digit_recognition.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore


## Future Improvements

* Collect more handwritten samples
* Improve class balance
* Increase the diversity of handwriting styles
* Experiment with deeper CNN architectures
* Deploy the model as a web or mobile application
