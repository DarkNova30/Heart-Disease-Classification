# Heart Disease Classification using Artificial Neural Networks (ANN)

![Heart Disease](https://img.shields.io/badge/Heart%20Disease%20Classification-ANN-brightgreen.svg)
![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange.svg)
![Keras](https://img.shields.io/badge/Keras-2.0%2B-red.svg)


An Artificial Neural Network (ANN) based project for predicting the likelihood of heart disease in patients based on various medical attributes.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Model Architecture](#model-architecture)


## Introduction
This project uses machine learning techniques, specifically an Artificial Neural Network (ANN), to classify whether a patient is likely to have heart disease or not. It aims to provide a valuable tool for early diagnosis and intervention in heart disease cases.

## Features
- Input features include various medical attributes such as age, sex, cholesterol levels, and more.
- Uses a deep learning ANN model to classify heart disease.
- Provides prediction probabilities and classification results.

## Model Architecture 
1. **Input Layer:** The input layer accepts the medical attributes of the patient, such as age, sex, cholesterol levels, and more. It preprocesses the data and passes it to the subsequent layers.

2. **Hidden Layers:** These layers are responsible for feature extraction and pattern recognition. The number of hidden layers and neurons per layer were selected to optimize the model's performance.

3. **Activation Functions:** Each hidden layer employs an activation function, such as ReLU (Rectified Linear Unit) or Sigmoid, to introduce non-linearity and capture complex relationships within the data.

4. **Output Layer:** The final layer is the output layer, which provides the binary classification result: whether the patient is likely to have heart disease or not. It uses the sigmoid activation function to produce prediction probabilities.

