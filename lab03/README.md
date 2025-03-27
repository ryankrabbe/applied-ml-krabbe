# Titanic Data Exploration

## Overview
In this project, I will use the Titantic dataset to explore different machine learning models to predict passenger survival. I'll incorporate different models and techniques and compare and constrast those models to see how the data is interpreted to predict survival rate.

## Dataset 
Titanic Dataset (Predict survival patterns based on features like age, sex, gender and fare)  
- We use the built-in dataset from seaborn:  
   - ```import seaborn as sns```
   - ```titanic = sns.load_dataset('titanic')``` 

---

## Project Outline

### Section 1. Import and Inspect the Data

### Section 2. Data Exploration and Preparation

### Section 3. Feature Selection and Justification

### Section 4. Train a Classification Model (Decision Tree)

### Section 5. Compare Alternative Models (SVC, NN)

### Section 6. Final Thoughts & Insights

## Below is my Summary Table Template
- This template is used to summarize my results across the different models and features used

| Model Type | Case | Features Used | Accuracy | Precision | Recall | F1-Score | Notes |
|------------|------|---------------|----------|-----------|--------|-----------|-------|
| **Decision Tree** | Case 1 | alone | 63% | 51% | 58% | 54% | - |
|                   | Case 2 | age | 61% | 50% | 17% | 26% | - |
|                   | Case 3 | age + family_size | 59% | 45% | 33% | 38% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| **SVM (RBF Kernel)** | Case 1 | 'age', 'fare', 'sex_encoded', 'alone', 'pclass' | 65% | 75% | 24% | 37% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| **SVM (Linear Kernel)** | Case 1 | 'age', 'fare', 'sex_encoded', 'alone', 'pclass' | 78% | 75% | 70% | 73% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| **SVM (Poly Kernel)** | Case 1 | 'age', 'fare', 'sex_encoded', 'alone', 'pclass' | 61% | 73% | 11% | 19% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| **SVM (Sigmoid Kernel)** | Case 1 | 'age', 'fare', 'sex_encoded', 'alone', 'pclass' | 62% | 54% | 50% | 52% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| **Neural Network (MLP)** | Case 1 | alone | 80% | 80% | 69% | 74% | - |