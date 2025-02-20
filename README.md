# Backward Elimination Model

## Overview
This project applies **Backward Elimination** to select the most significant features for predicting profit in a startup dataset. The model utilizes multiple regression techniques and feature selection methods to improve predictive accuracy.

## Dataset
- The dataset used: `50_Startups.csv`
- Features include:
  - **R&D Spend**
  - **Administration**
  - **Marketing Spend**
  - **State (Categorical feature)**
  - **Profit (Target Variable)**

## Implementation Steps
1. **Data Preprocessing**:
   - Handling missing values and duplicates.
   - Encoding categorical variables.
   - Data visualization using heatmaps and scatter plots.

2. **Feature Selection Using Backward Elimination**:
   - Start with all features in the model.
   - Iteratively remove the least significant feature based on p-values.
   - Evaluate model performance after each elimination step.

3. **Model Training & Evaluation**:
   - Train a multiple linear regression model.
   - Evaluate using metrics like Mean Absolute Error (MAE) and R-squared score.

## Dependencies
- Python (pandas, numpy, seaborn, matplotlib, scikit-learn, statsmodels)

## Usage
Run the Jupyter Notebook to execute the analysis and visualize the results.

## Results
The final model includes only the most relevant features, improving prediction accuracy by reducing overfitting.

