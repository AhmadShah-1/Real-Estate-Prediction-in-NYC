# Real Estate Prediction in NYC


## Overview
This project leverages machine learning to predict property values in New York City by analyzing historical data from NYC Open Data. The project tackles common issues in real estate prediction, such as:
- Incomplete datasets with missing values.
- Variances in data collected over different time periods.
- The need for robust cross-validation and hyperparameter tuning for accurate predictions.
- Visualization of spatial property value predictions over NYC.

By integrating rigorous data preprocessing, model comparisons, and advanced visualization techniques, the project provides stakeholders with an informative tool to analyze market trends and make informed decisions.

## Features
- **Data Preprocessing:**  
  - Aggregates multiple datasets covering different time ranges.
  - Performs data cleaning including imputation of missing values, outlier removal, and feature scaling.
  - Harmonizes dataset structure via column mapping to ensure consistency.

- **Machine Learning Pipeline:**  
  - Compares several regression models: Linear Regression, Random Forest Regressor, and XGBRegressor.
  - Uses cross-validation techniques (k-fold, repeated stratified k-fold) to evaluate model performance.
  - Implements GridSearchCV for hyperparameter optimization with evaluation metrics such as Mean Squared Error (MSE) and R-squared.

- **Visualization & Analysis:**  
  - Generates scatter plots comparing actual vs. predicted property values.
  - Creates geographic heat maps (using Cartopy and Matplotlib) to illustrate spatial trends in property valuations.
  - Offers an interactive component where users can enter parameters (e.g., year, property features) to receive tailored predictions.

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Real-Estate-Prediction-in-NYC.git
   cd Real-Estate-Prediction-in-NYC

   
