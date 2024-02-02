# House Price Prediction Model

This repository contains code for a machine learning model to predict house prices based on the provided dataset. The model uses XGBoost regressor and is implemented in Python.

## Dataset

The dataset used for training the model is provided in two CSV files:

- `train.csv`: Training data with features and target variable (`SalePrice`).
- `test.csv`: Test data for making predictions.

## Data Preprocessing

The code includes data preprocessing steps such as handling missing values, encoding categorical variables, and creating a pipeline for the XGBoost regressor model.

## Model Training

The XGBoost regressor is used for training the model with hyperparameter tuning. The optimal hyperparameters are determined through cross-validation.

## Visualization

The results of hyperparameter tuning are visualized in a 3D scatter plot, showing the relationship between the number of estimators, learning rate, and the mean absolute error.

## Model Deployment

The trained model is saved using pickle and can be loaded for making predictions on new data. The predictions on the test set are saved in a CSV file named `submission.csv`.

## Usage

To use the model for predictions, follow these steps:

1. Install the required dependencies:

   ```bash
   pip install -r requirements.txt

## conclusions

The machine learning model successfully predicts house prices based on the provided dataset. Feel free to explore the code and adapt it for your own projects.