# House_Price_Linear_and_Multi_Regression Project

## Overview

Implement and understand Simple & Multiple Linear Regression as Import and preprocess the dataset, Split data into train-test sets, Fit a Linear Regression model using sklearn.linear_model, Evaluate model using MAE, MSE, R² and Plot regression line and interpret coefficients.

## Project Structure

- The end-to-end code.
- Interview questions & answers.
- Dataset: `Housing.csv` (place in project directory).

## Steps Covered

1. **Data Loading & Preprocessing**
2. **Feature Engineering (encoding categoricals)**
3. **Train-test Split**
4. **Linear Regression using Scikit-learn**
5. **Model Evaluation: MAE, MSE, R²**
6. **Regression Line Visualization**
7. **Coefficient Interpretation & Multicollinearity**


## Code Block Explanations

Imports: Standard libraries (Pandas, NumPy), Scikit-learn for ML, Matplotlib for visualization.

Load & Preview: Read CSV and check structure.

Preprocessing: Convert categorical yes/no to 1/0 and 'furnishingstatus' to dummy variables.

Model Preparation: Select features and label, split data into training and testing.

Modeling: Fit linear regression, predict test values.

Evaluation: Metrics (MAE, MSE, R²) provide insight into model accuracy.

Visualization: Shows actual vs. predicted house prices for 'area' (simple regression display).

Coefficient Reporting: Show the impact of each feature.
