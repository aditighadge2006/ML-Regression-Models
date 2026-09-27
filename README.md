# House Price Prediction using Regression

## Project Overview

This project implements regression models for predicting house prices based on house area.

Two approaches are implemented:

1. Linear Regression using Scikit-learn
2. Linear Regression using Gradient Descent optimization

## Dataset

The dataset contains:

- Area of the house in square feet
- House Price in ₹ lakh

Example data:

| Area (sq.ft) | Price (₹ lakh) |
|--------------|----------------|
| 500 | 25 |
| 700 | 32 |
| 900 | 40 |
| 1100 | 48 |
| 1300 | 55 |
| 1500 | 65 |
| 1700 | 72 |
| 1900 | 82 |
| 2100 | 90 |
| 2300 | 100 |

## Algorithms Used

### 1. Linear Regression

Linear Regression is used to establish a relationship between house area and house price and predict the price of a house.

### 2. Gradient Descent

Gradient Descent is implemented to optimize the slope and intercept of the linear regression model by minimizing the cost function.

## Performance Metrics

The models are evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Results

### Linear Regression

- MAE: 0.7442
- MSE: 1.0388
- RMSE: 1.0192
- R² Score: 0.9982

### Gradient Descent

- MAE: 2.2590
- MSE: 6.3600
- RMSE: 2.5219
- R² Score: 0.9889

## Prediction Example

For a house with an area of 1800 sq.ft:

- Linear Regression predicts approximately ₹77.54 lakh.
- Gradient Descent predicts approximately ₹76.62 lakh.

## Tools and Libraries

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Files

`ML_Regression_House_Price.ipynb` contains the complete implementation, graphs, predictions and performance evaluation.

## Conclusion

The project demonstrates the implementation and evaluation of Linear Regression and Gradient Descent for house price prediction. The performance of both approaches is evaluated using standard regression metrics.
