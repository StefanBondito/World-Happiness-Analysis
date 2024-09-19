# World-Happiness-and-Corruption-Regression-Analysis
![dataset-cover](https://github.com/user-attachments/assets/88720d4a-91ff-43ba-b780-16ac30054bbb)

A Data Mining and Visualization project to analyze factors that affects happiness of the world population using World Happiness. After that, the models used will be compared using R-Square and Residual Standard Error.

# Workflow
## Data Collection
[Happiness and Corruption 2015-2020] (https://www.kaggle.com/datasets/eliasturk/world-happiness-based-on-cpi-20152020) from Kaggle

## Data Preprocessing
1. Clean out missing data
2. Check correlation between the variables
3. Create a base Linear Regression model to check assumptions (Normality, Homoscedasticity, Autocorrelation, Multicollinearity)
4. Create models of Linear, Logistic, and Robust Regression
5. Compare the models with their metrics (R-Square, MSE, MAE)

## Model
We trained 3 models which are Linear Regression, Logistic Regression, Robust Regression  to find the best one. The model with the highest R-Square value and or lowest RMSE and MSE score would be considered as the perfect model.
