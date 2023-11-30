# Predicting-saleprice-of-houses-RandomForest-Model-Pipeline
# House Price Prediction

This project involves predicting house prices using machine learning. The code is written in Python and utilizes the scikit-learn library for machine learning tasks.
The Jupyter Notebook in this repository contains code for a house price prediction model. The model is trained on a dataset consisting of various features related to houses, and it aims to predict the sale prices.

## Dependencies

- Python 3.10.12
- Required Libraries:
  - pandas
  - scikit-learn

## Usage

1. Open the Jupyter Notebook (`house_price_prediction.ipynb`) using a Jupyter Notebook environment or a compatible platform.
2. Execute the code cells sequentially to load the data, preprocess it, train the machine learning model, and make predictions.
3. The trained model is evaluated using Mean Absolute Error (MAE) on a validation set.

## Data

The dataset is assumed to be in CSV format and is loaded from the following files:
- `train.csv`: Training data containing features and target variable.
- `test.csv`: Test data for making predictions.

## Model

The machine learning model used is a Random Forest Regressor, configured with 150 estimators.

## Preprocessing

The data preprocessing involves handling missing values, separating categorical and numerical features, and applying one-hot encoding to categorical features.

## Evaluation

The model is evaluated using the Mean Absolute Error (MAE) metric on a validation set.

## Making Predictions

After training the model, predictions are made on the test data, and the results are saved to a CSV file (`submission.csv`).

Feel free to explore and modify the code to suit your needs!

