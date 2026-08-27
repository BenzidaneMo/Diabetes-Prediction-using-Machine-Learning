# Diabetes Prediction using Machine Learning

A simple machine learning project that predicts whether a person has diabetes using the **Pima Indians Diabetes Dataset**.

The project was created as a practical exercise to review data preprocessing, feature scaling, classification algorithms, model evaluation, and ensemble learning.

## Models

The following models are implemented and compared:

* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest
* Artificial Neural Network (ANN)
* ANN + SVM Soft-Voting Ensemble

## Features

* Data exploration and correlation analysis
* Missing-value inspection
* Feature preprocessing
* Standard feature scaling
* Train/test split with stratification
* Multiple classification models
* ANN with early stopping
* ANN + SVM probability-based ensemble
* Confusion matrix
* Accuracy, precision, recall, and F1-score comparison

## Dataset

The project uses the **Pima Indians Diabetes Dataset**, which contains medical diagnostic measurements used to predict diabetes.

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* TensorFlow / Keras

## How to Run

Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn tensorflow
```

Then run the notebook:

```text
Detecting diabetes.ipynb
```

## Project Structure

```text
.
├── Detecting diabetes.ipynb
├── pima-data.csv
└── README.md
```

## Purpose

This project is primarily a learning exercise focused on understanding and comparing traditional machine learning algorithms with neural networks and a simple ensemble approach.
