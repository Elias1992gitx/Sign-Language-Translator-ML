# Ethiopian Sign Language to Amharic text Translator (ML)

This repository contains a project for developing a translator system that converts Ethiopian Sign Language gestures into Amharic text. The system is built using Long Short-Term Memory (LSTM) neural networks implemented in TensorFlow and Keras. The project also includes sample data for training and testing the model, as well as pre-trained models in both .h5 and .tflite formats.

## Overview

Ethiopian Sign Language (ESL) is the primary means of communication for deaf individuals in Ethiopia. However, there is a lack of efficient tools for translating ESL gestures into written or spoken languages. This project aims to bridge this gap by developing a Deep learning-based translator system that can interpret ESL gestures and produce Amharic text.

## Requirements

- Python 3
- TensorFlow
- Keras
- Other necessary machine and Deep learning frameworks and libraries

## Usage

### Training the Model

1. Prepare your training data. The data should consist of ESL gesture images and corresponding Amharic text labels.

2. Run the training script:

### Testing the Model

1. Prepare your testing data. This should be separate from the training data.

2. Run the testing script:

### Translating ESL Gestures

1. Once the model is trained, you can use it to translate ESL gestures into Amharic text.

2. Deploy the model using the provided .h5 or .tflite files.

3. Integrate the deployed model into your desired application or interface for real-time translation.

## Model Files

- `model.h5`: Pre-trained LSTM model saved in HDF5 format.
- `model.tflite`: Pre-trained LSTM model converted to TensorFlow Lite format for deployment on mobile and embedded devices.

## Sample Data

The `MP_DATA/` directory contains sample data for training and testing the model. Feel free to use this data to get started with training and evaluation.

## Acknowledgments

- This project was inspired by the need for efficient communication tools for deaf (hearing impaired) individuals in Ethiopia.
