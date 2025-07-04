# Facial-Emotion-Recognition-using-CNN
This project implements a deep learning approach to recognize facial emotions from grayscale images using a Convolutional Neural Network (CNN). It leverages the FER2013 dataset, preprocessed and augmented using `ImageDataGenerator`. The model is trained to classify emotions such as angry, happy, sad, surprise, and neutral.

## Features

- Uses TensorFlow and Keras for CNN model building
- Applies data augmentation to enhance training robustness
- Performs grayscale image processing and histogram equalization
- Evaluates performance using confusion matrix and classification report
- Classifies emotions into categories like Angry, Happy, Sad, Neutral, Surprise, etc.

## Dataset

The FER2013 dataset is organized into `train/` and `test/` directories, with images sorted into subfolders based on emotion labels.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib
- scikit-learn
- seaborn

## How to Run

1. Mount Google Drive and extract dataset archive.
2. Run the notebook in Google Colab or a local Jupyter environment.
3. Train the model and observe validation accuracy and metrics.
4. Evaluate test accuracy and view the confusion matrix.

## Output

- Trained CNN model
- Accuracy and loss plots
- Confusion matrix and classification report
