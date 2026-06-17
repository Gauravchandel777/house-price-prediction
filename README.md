# House Price Prediction Using Machine Learning

## Project Overview

This project predicts house prices using Machine Learning. The model is trained on a housing dataset obtained from Kaggle and uses important house features to estimate the selling price of a house.

## Dataset

The dataset was obtained from Kaggle Housing Price Prediction Dataset.

Features used in this project:

- OverallQual (Overall Quality)
- GrLivArea (Ground Living Area)
- GarageCars (Garage Capacity)
- TotalBsmtSF (Total Basement Area)

Target Variable:

- SalePrice (House Price)

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-Learn
- GitHub

## Machine Learning Algorithm

The project uses Linear Regression for predicting house prices.

## Project Workflow

1. Download dataset from Kaggle
2. Load dataset into Google Colab
3. Select important features
4. Split dataset into training and testing sets
5. Train Linear Regression model
6. Generate predictions
7. Evaluate model performance

## Code Example

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X_train, y_train)

prediction = model.predict(X_test)
