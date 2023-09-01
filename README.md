# Deep Learning Heart Disease Prediction

## Project Overview
This project aims to predict heart disease using deep learning techniques. Heart disease is a critical health issue globally, and early detection plays a pivotal role in prevention and intervention. Leveraging a heart failure prediction dataset from Kaggle, this project employs various deep learning models for binary classification to predict the presence or absence of heart disease.

## Data Source
The dataset used in this project is a collection of data from different sources, including Cleveland, Hungary, Switzerland, and VA Long Beach, providing valuable patient attributes and corresponding heart disease labels.

## Objective
The primary objective of this project is to build, train, and evaluate deep learning models to classify whether a patient has heart disease based on their clinical data.

## Key Components
- **Data Preparation:** The dataset is preprocessed by encoding categorical features into numerical values and standardizing the numerical attributes.

- **Model Development:** Several neural network models are created and evaluated:
  - Baseline Model: A simple model with one hidden layer.
  - Overfitting Model: An intentionally overfit model to study the impacts of overfitting.
  - Regularized Model: Models with regularization techniques like dropout layers and L1 regularization.
  - Best Model: The top-performing model is chosen based on accuracy and generalization.

- **Model Evaluation:** Model performance is assessed through training and validation loss/accuracy plots, and the best model is tested on a separate test dataset using ROC AUC as a key metric.

## Conclusion
This project provides a comprehensive exploration of using deep learning for heart disease prediction. The best model, identified through rigorous evaluation, offers a promising approach for early detection of heart disease based on clinical data.

*For detailed implementation and code, please refer to the Jupyter Notebook within this repository.*
