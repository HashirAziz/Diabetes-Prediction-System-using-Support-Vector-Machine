# Diabetes-Prediction-System-using-Support-Vector-Machine

# Diabetes Prediction System

Welcome to the Diabetes Prediction System! This project uses Support Vector Machine (SVM) for predicting whether a person is diabetic based on medical input data. The system is designed to provide an easy-to-use interface for predicting diabetes using a trained machine learning model.

## Table of Contents

- [Project Description](#project-description)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Project Description

This project involves building a machine learning model to predict diabetes based on a variety of medical attributes. The model is trained using the Support Vector Machine (SVM) algorithm, which is known for its effectiveness in classification problems. The project includes:

1. Data preprocessing and normalization
2. Model training and evaluation
3. A command-line interface (CLI) for predicting diabetes

## Dataset

The dataset used for training the model is the Pima Indians Diabetes Dataset, which includes various medical details such as:

- Number of pregnancies
- Glucose level
- Blood pressure
- Skin thickness
- Insulin level
- BMI (Body Mass Index)
- Diabetes pedigree function
- Age

## Model Training

The SVM model is trained on the normalized dataset. The steps include:

1. Splitting the dataset into training and testing sets.
2. Normalizing the data using `StandardScaler`.
3. Training the SVM model on the training data.
4. Evaluating the model on the testing data.
