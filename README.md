# Machine Learning - Screen Time Health Impact (HW2)

**Home Assignment 2 (Grade 95, M.Sc. Data Science, HIT). An advanced Machine Learning project analyzing the health effects of screen time on children and youth in India. Based on the [Kaggle Indian Kids Screentime 2025](https://www.kaggle.com/datasets/ankushpanday2/indian-kids-screentime-2025) dataset.**

## Overview
This project investigates the relationship between screen habits (age, gender, device type, usage ratios) and health outcomes (anxiety, poor sleep, eye strain) among 9,712 Indian children. The study involves a comprehensive comparison of seven different machine learning algorithms, focusing on feature interaction and model stability.

## Key Features
- **Advanced EDA & Feature Engineering:** Created interaction terms and domain-specific features to uncover deep relationships between device usage and health metrics.
- **Algorithm Comparison:** Evaluated 7 different models, including Logistic Regression, Decision Trees, Random Forest, and XGBoost.
- **Winning Model - XGBoost:** Achieved a peak **accuracy of 86%**. The model was fine-tuned to eliminate overfitting issues, ensuring high generalization on test data.
- **Demographic Insights:** Analysis of urban vs. rural differences and the impact of exceeding IAP (Indian Academy of Pediatrics) guidelines.

## Tech Stack
- **Language:** Python
- **Libraries:** Scikit-learn, XGBoost, Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn

## Repository Structure
- `Screen_Time_Health_Impact_Analysis.ipynb`: Full implementation, including hyperparameter optimization and model selection.
- `assignment 2.pdf`: Original assignment instructions and requirements.
- `Indian_Kids_Screen_Time.csv`: The dataset used for the analysis.
