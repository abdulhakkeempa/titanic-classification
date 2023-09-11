# Titanic Classification

Exploratory Data Analysis and Prediction on the survival of titanic dataset.

https://www.kaggle.com/competitions/titanic/

## Results

| Algorithm | Scaled | Accuracy | Precision (0,1) | Recall (0,1) | Kaggle Score |
| :---:         |     :---:      |      :---:      |      :---:      | :---:      |   :---: |
| Logistic Regression  | StandardScaler     | 0.7847    | 0.85, 0.69 | 0.81, 0.74 | 0.7488
| Logistic Regression (One-Hot Encoded) | StandardScaler     | 0.7802    | 0.82, 0.71 | 0.82, 0.72 | 0.76315
| Support Vector Classifer (Polynomial Kernel) | MinMaxScaler     | 0.798    | 0.88, 0.67 | 0.81, 0.77 | 0.77990
