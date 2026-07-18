# Algerian Forest Fires Prediction using Ridge, Lasso & ElasticNet Regression

## Project Overview

This project demonstrates the complete Machine Learning workflow for predicting the **Fire Weather Index (FWI)** using meteorological and environmental data from the **Algerian Forest Fires Dataset**.

The project covers:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Model Training
- Regularization Techniques
- Performance Evaluation

Instead of using only Linear Regression, this project focuses on three powerful regularization algorithms:

- Ridge Regression (L2 Regularization)
- Lasso Regression (L1 Regularization)
- ElasticNet Regression (Combination of L1 & L2)

These techniques help reduce overfitting and improve model generalization.

---

# Project Structure

```
Forest-Fire-Prediction/
│
├── data/
│   ├── Algerian_forest_fires_dataset.csv
│   └── Algerian_forest_fires_dataset_cleaned.csv
│
├── notebooks/
│   ├── Ridge_Lasso_ElasticNet_EDA.ipynb
│   └── Model_Training.ipynb
│
├── README.md
└── requirements.txt
```

---

# Dataset Information

### Dataset Name

Algerian Forest Fires Dataset

### Source

UCI Machine Learning Repository

The dataset contains weather observations collected from two regions of Algeria during June to September.

The objective is to predict the **Fire Weather Index (FWI)** based on different environmental factors.

---

# Dataset Features

| Feature | Description |
|----------|-------------|
| Temperature | Air Temperature (°C) |
| RH | Relative Humidity (%) |
| Ws | Wind Speed (km/h) |
| Rain | Rainfall (mm) |
| FFMC | Fine Fuel Moisture Code |
| DMC | Duff Moisture Code |
| DC | Drought Code |
| ISI | Initial Spread Index |
| BUI | Build Up Index |
| Classes | Fire / Not Fire |
| Region | Region Identifier |
| FWI | Fire Weather Index (Target Variable) |

---

# Target Variable

```
FWI (Fire Weather Index)
```

FWI is a numerical indicator representing the intensity and danger level of forest fires.

Higher values indicate:

- Higher fire risk
- Faster fire spread
- Greater fire intensity

---

# Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary rows
- Removed missing values
- Converted categorical columns into numerical values
- Feature selection
- Data type conversion
- Saved cleaned dataset
- Train-Test Split
- Standardization using StandardScaler

---

# Exploratory Data Analysis

EDA includes:

- Checking missing values
- Dataset information
- Statistical summary
- Correlation analysis
- Distribution plots
- Box plots
- Heatmap
- Outlier detection

The relationships between weather parameters and the Fire Weather Index were analyzed before model training.

---

# Machine Learning Models

Three regression models were trained:

## 1. Ridge Regression

Uses L2 Regularization.

Advantages:

- Prevents overfitting
- Handles multicollinearity
- Keeps all features

---

## 2. Lasso Regression

Uses L1 Regularization.

Advantages:

- Performs feature selection
- Removes less important features
- Produces sparse models

---

## 3. ElasticNet Regression

Combination of:

- L1 Regularization
- L2 Regularization

Advantages:

- Better feature selection
- Better handling of correlated variables
- Improved model stability

---

# Libraries Used

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

# Model Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help compare prediction accuracy and model performance.

---

# Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
EDA
      │
      ▼
Feature Engineering
      │
      ▼
Train-Test Split
      │
      ▼
Feature Scaling
      │
      ▼
Model Training
      │
      ▼
Prediction
      │
      ▼
Performance Evaluation
```

---

# Key Learning Outcomes

Through this project, I learned:

- Data Cleaning using Pandas
- Exploratory Data Analysis
- Correlation Analysis
- Feature Engineering
- Data Standardization
- Train-Test Split
- Ridge Regression
- Lasso Regression
- ElasticNet Regression
- Model Evaluation
- Performance Comparison

---

# Project Highlights

✔ Data Cleaning

✔ Exploratory Data Analysis

✔ Correlation Heatmap

✔ Feature Scaling

✔ Ridge Regression

✔ Lasso Regression

✔ ElasticNet Regression

✔ Model Comparison

✔ Regression Metrics

---

# Concepts Covered

- Machine Learning
- Supervised Learning
- Regression
- Regularization
- Feature Engineering
- StandardScaler
- Model Evaluation
- Data Visualization

---

# Future Improvements

Possible future enhancements include:

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Pipeline implementation
- Model serialization using Pickle
- Flask/FastAPI deployment
- Interactive web application
- Real-time prediction API

---

# Author

**Anant Vyas**

Mechanical Engineering Undergraduate

Currently learning:

- Python
- SQL
- Machine Learning
- Data Science
- Deep Learning

