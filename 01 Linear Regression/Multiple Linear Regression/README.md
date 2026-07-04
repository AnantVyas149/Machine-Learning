# Multiple Linear Regression

## Project Overview

This project demonstrates the implementation of **Multiple Linear Regression** using Python and Scikit-learn to predict an economic index based on multiple independent variables.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature scaling, model training, cross-validation, prediction, evaluation, and residual analysis.

---

## Objectives

- Understand the working of Multiple Linear Regression.
- Explore relationships between multiple features and the target variable.
- Train a regression model using Scikit-learn.
- Evaluate model performance using regression metrics.
- Validate model performance using Cross Validation.

---

## Dataset

**Dataset:** Economic Index Dataset

### Features

- Interest Rate
- Unemployment Rate

### Target Variable

- Index Price

---

## Technologies & Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Exploratory Data Analysis

The following analyses were performed:

- Dataset inspection
- Statistical summary
- Missing value check
- Correlation analysis
- Scatter plots
- Regression plots
- Feature relationship visualization

---

## Machine Learning Workflow

1. Load the dataset
2. Remove unnecessary columns
3. Perform Exploratory Data Analysis (EDA)
4. Select independent and dependent variables
5. Split the dataset into training and testing sets
6. Standardize the features using StandardScaler
7. Train a Multiple Linear Regression model
8. Perform Cross Validation
9. Make predictions
10. Evaluate model performance
11. Analyze residuals

---

## Model Performance

| Metric | Value |
|---------|--------|
| Mean Absolute Error (MAE) | **59.94** |
| Mean Squared Error (MSE) | **5793.76** |
| Root Mean Squared Error (RMSE) | **76.12** |
| R² Score | **0.8279** |

The model achieved an **R² Score of approximately 82.8%**, indicating a strong relationship between the selected economic indicators and the target variable.

---

## Project Structure

```
02_Multiple_Linear_Regression
│
├── data
│   └── economic_index.csv
│
├── images
│
├── Multiple_regression.ipynb
│
└── README.md
```

---

## Key Concepts Covered

- Multiple Linear Regression
- Feature Selection
- Train-Test Split
- Feature Scaling
- StandardScaler
- Cross Validation
- Model Prediction
- Regression Evaluation Metrics
- Residual Analysis

---

## Visualizations

The notebook includes:

- Correlation Matrix
- Scatter Plots
- Regression Plots
- Residual Distribution
- Residual vs Predicted Values Plot

---

## Future Improvements

- Perform Feature Engineering
- Check Multicollinearity using VIF
- Apply Ridge Regression
- Apply Lasso Regression
- Hyperparameter Tuning
- Compare Multiple Regression with other regression models

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Building regression models using Scikit-learn
- Preparing data for machine learning
- Evaluating regression performance
- Understanding model assumptions
- Performing residual analysis
- Using cross-validation to assess model generalization

---

## Author

**Anant Vyas**

Mechanical Engineering Undergraduate  
Python | Data Analytics | Machine Learning