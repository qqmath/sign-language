# Sign Language Detector Model

## Project Overview
This repository contains the implementation of a Sign Language Detector Model using TensorFlow and Keras. The model is designed to recognize and classify different sign language gestures from images, making it a valuable tool for facilitating communication with the deaf and hard-of-hearing community.

## Features
- **Image Classification**: Classifies sign language gestures into 27 different classes, including all 26 letters of the English alphabet and a 'Blank' gesture.
- **Deep Learning Model**: Utilizes Convolutional Neural Networks (CNNs) for feature extraction and classification.
- **Data Augmentation**: Implements `ImageDataGenerator` for image preprocessing and augmentation to improve model robustness.

## Prerequisites
- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Installation and Setup
1. Clone the repository to your local machine.
2. Install the required Python packages:
   ```bash
   pip install numpy pandas matplotlib seaborn tensorflow keras
   ```
3. Download the dataset for Sign Language (links can be provided in the dataset section).

## Dataset
The model is trained and validated on a dataset containing images of various sign language gestures. The dataset should be organized into three folders: `Train_Alphabet`, `Test_Alphabet`, and `Validation_Alphabet`.

## Model Training
1. The model architecture includes multiple `Conv2D` and `MaxPooling2D` layers, followed by `Flatten`, `Dense`, and `Dropout` layers.
2. The model is compiled with Adam optimizer and categorical crossentropy loss function.
3. Train the model using the `fit` method on the training and validation data.

## Usage
1. Load the model using Keras.
2. Preprocess the input image to the required format.
3. Use the model to predict the sign language gesture.

## TODO

Complete setting up the web app for the model.

## Results and Evaluation

![alt text](https://github.com/qqmath/sign-language/blob/main/performance.png
)


## Acknowledgements
Special thanks to all the contributors and researchers in the field of sign language recognition for their valuable insights and datasets.

