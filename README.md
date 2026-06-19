# Case_Study_on_Preprocessing
# House Price Dataset Preprocessing

## Overview

This project demonstrates a complete data preprocessing workflow for a House Price Prediction dataset. The notebook covers data cleaning, missing value treatment, feature engineering, encoding, scaling, feature selection, outlier handling, and train-test splitting to prepare the dataset for machine learning models.

---

## Project Workflow

### 1. Data Exploration
- Load dataset using Pandas
- Inspect structure and data types
- Generate descriptive statistics
- Check dataset dimensions

### 2. Data Cleaning
- Remove duplicate records
- Handle missing values
- Drop columns with excessive missing data
- Remove rows with missing target values

### 3. Feature Engineering
- Extract Day, Month, and Year from the sale date
- Remove the original date column

### 4. Data Transformation
#### Scaling
- Min-Max Scaling applied to numerical features

#### Encoding
- Label Encoding for binary categorical variables
- One-Hot Encoding for multi-category features

### 5. Feature Selection
- Mutual Information Regression
- Retain features with significant predictive power

### 6. Outlier Detection and Treatment
- Visualize outliers using Box Plots
- Handle outliers using IQR-based clipping

### 7. Train-Test Split
- Training Set: 80%
- Testing Set: 20%

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

 Science Enthusiast
