# Sonar Data - Rock vs. Mine Prediction

## Overview

This project focuses on predicting whether an object detected by sonar data is a rock or a mine. The classification model is built using Logistic Regression and evaluated on training and test datasets.

## Dataset

The sonar data is loaded into a Pandas DataFrame from the file 'sonar data.csv'. This dataset contains features representing sonar signal patterns, and the target variable is binary ('M' for Mine, 'R' for Rock).

- Number of rows and columns: [provide the shape]
- Statistical measures: [include key statistics]
- Distribution of target classes:
  - 'M' (Mine): [count]
  - 'R' (Rock): [count]

## Data Processing

The dataset is split into features (X) and the target variable (Y). Further, a train-test split is performed using Scikit-learn's `train_test_split` function, ensuring a 90-10 split ratio with stratification.

## Model Training

A Logistic Regression model is trained using the training data.

## Model Evaluation

The model's performance is assessed on both the training and test datasets. Accuracy scores are calculated to measure the effectiveness of the model.

- Accuracy on training data: [accuracy score]
- Accuracy on test data: [accuracy score]

## Predictive System

A predictive system is implemented using the trained model. An example input is provided, and the model predicts whether the object is a rock or a mine.

## Dependencies

- NumPy
- Pandas
- Scikit-learn

## How to Use

1. Ensure you have the required dependencies installed.
2. Run the provided code cells in a Jupyter Notebook or any Python environment.
3. View the accuracy scores and the prediction for the example input.

## Author

Anmol Yaseen

## License

This project is licensed under the [MIT License](LICENSE).

Happy Coding!
