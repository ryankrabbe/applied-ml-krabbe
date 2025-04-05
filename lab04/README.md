# Titanic Data Exploration

## Overview
In this project I'll use the Titantic dataset to predict `fare` based on different features such as `age`, `sex`, `pclass` and `family_size`. I'll incorporate different machine models and techniques to predict passenger fare.

## Dataset 
Titanic Dataset (Predict passenger fare based on features like `age`, `sex`, `pclass` and `family_size`)  
- We use the built-in dataset from seaborn:  
   - ```import seaborn as sns```
   - ```titanic = sns.load_dataset('titanic')``` 

---

## Project Outline

### Section 1. Import and Inspect the Data

### Section 2. Data Exploration and Preparation

### Section 3. Feature Selection and Justification

### Section 4. Train a Regression Model (Linear Regression)

### Section 5. Compare Alternative Models (Ridge, Elastic Net, Polynomial Regression)

### Section 6. Final Thoughts & Insights

## Below is my Summary Table Template
- This template is used to summarize my results across the different models

| Model                  | R² (Test) | RMSE (Test) | MAE (Test) | Notes                                               |
|------------------------|-----------|-------------|------------|-----------------------------------------------------|
| Linear Regression      | 0.350     | 30.66       | 20.48      | Performed well due to features selected          |
| Ridge Regression       | 0.351     | 30.65       | 20.45      | Improved from Linear Regression due to regularization         |
| ElasticNet Regression  | 0.379     | 29.98       | 19.05      | Generalization was improved due to balance L1 + L2 penalties  |
| Polynomial Regression  | 0.447     | 28.29       | 17.32      | Performed the best due to ability to model non-linear relationships between features      |