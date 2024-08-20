# Linear Regression - Predicting Product Sales

This repository contains the project files for the linear regression analysis of product sales based on various factors. The main objective of this project was to build a model to predict product sales using data from summer products with rating and performance metrics.

## Project Files

- **HW_3_Project_Report.pdf**: The detailed project report explaining the steps, methodologies, and findings of the linear regression analysis.
- **summer-products-with-rating-and-performance_Harshaanth.xlsx**: The dataset used for analysis, containing product ratings and performance metrics.
- **README.md**: Project overview and description (this file).

## Project Overview

The goal of this project was to analyze and predict product sales using linear regression models. The analysis was performed using the `summer-products-with-rating-and-performance` dataset. The key steps involved in this analysis include:

1. **Data Visualization**:
   - Histograms of all numerical variables were plotted to check their distribution.
   - Log transformation was applied to the `units_sold` variable due to its skewed distribution.

2. **Scatter and Box Plots**:
   - Scatter plots were created to visualize the relationship between `log_units_sold` and other numerical variables.
   - Box plots were generated to compare `log_units_sold` against categorical variables.

3. **Linear Regression Models**:
   - A linear regression model was initially run using all predictors. The significant variables were identified, and the model's performance on both training and validation data was assessed.
   - A stepwise variable selection was performed to simplify the model by removing insignificant predictors, leading to a more efficient model.

4. **Model Comparison**:
   - The models were compared using performance metrics such as RMSE. The simplified model (Model B) was chosen for its better predictive accuracy and lack of multicollinearity issues.

5. **Prediction**:
   - The final model was used to predict the number of units sold for a hypothetical product scenario.

## Key Findings

- **Significant Predictors**: The presence of a merchant profile picture, product rating, and merchant rating were found to be significant predictors of product sales.
- **Model Performance**: The simplified model showed comparable performance to the full model but was preferred due to its simplicity and lack of multicollinearity.

## Conclusion

The linear regression model developed in this project effectively predicts product sales based on selected significant variables. The model is robust and performs well on new data, making it a valuable tool for predicting sales in similar contexts.
