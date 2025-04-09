# Ensemble Models - Wine Quality Dataset

## Overview
In this project I'll use the Titantic dataset to predict `fare` based on different features such as `age`, `sex`, `pclass` and `family_size`. I'll incorporate different machine models and techniques to predict passenger fare.

## Dataset 
Wine Quality Dataset
- The dataset includes 11 physicochemical input variables (features):
    - `fixed acidity`
    - `volatile acidity`
    - `citric acid`
    - `residual sugar` 
    - `chlorides`
    - `free sulfur dioxide`
    - `total sulfur dioxide`
    - `density`
    - `pH`
    - `sulphates`
    - `alcohol`
- The target variable is quality (integer score from 0 to 10, rated by wine tasters)

---

## Project Outline

### Section 1. Load and Inspect the Data

### Section 2. Prepare the Data

### Section 3. Feature Selection and Justification

### Section 4. Split the Data into Train and Test

### Section 5. Evaluate Model Performance (Choose 2)

### Section 6. Compare Results

### Section 7. Conclusion and Insights

---

## Below is my Summary Table Template
- This template is used to compare my two ensemble models used: Gradient Boosting & Voting (RF + LR + KNN)

| Model                    | Train Accuracy | Test Accuracy | Train F1   | Test F1   | Accuracy Gap | F1 Gap   |
|--------------------------|----------------|----------------|------------|-----------|---------------|----------|
| Gradient Boosting (100)  | 0.960125       | 0.856250       | 0.958410   | 0.841106  | 0.103875      | 0.117304 |
| Voting (RF + LR + KNN)   | 0.913213       | 0.853125       | 0.892945   | 0.821034  | 0.060088      | 0.071911 |
