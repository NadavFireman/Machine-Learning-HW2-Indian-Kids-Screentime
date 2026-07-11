# Machine Learning - Screen Time Health Impact (HW2)

**Assignment Solution (Grade 95, M.Sc. Data Science, HIT). Binary health-impact classification for 9,712 Indian children, based on the [Kaggle Indian Kids Screentime 2025](https://www.kaggle.com/datasets/ankushpanday2/indian-kids-screentime-2025) dataset.**

## Key Features
- **Feature Engineering:** Engineered the target (`Healthy`, derived from the multi-label health-impacts field) plus interaction and domain features — age × screen-time interaction, teen flag, and recreational-hours decomposition.
- **Algorithm Comparison:** 7 classifiers (Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, AdaBoost, KNN, XGBoost) evaluated with explicit train-test gap tracking across accuracy, precision, recall, and F1 to flag overfitting.
- **Winning Model — XGBoost:** 86% test accuracy with the best accuracy-generalization balance across all configurations.
- **Explainability (SHAP):** Test-set summary plot identifying the dominant screen-time drivers of health outcomes.
- **Demographic Insights:** Urban vs. rural comparison and analysis of children exceeding the recommended screen-time limits (IAP guidelines).

## Results
XGBoost on the held-out test set: **accuracy = 86%** — selected over 6 competing models for combining top accuracy with the smallest train-test gaps.

## Repository Structure
- `Screen_Time_Health_Impact_Analysis.ipynb`: Full implementation (Hebrew narrative; code and charts are language-independent).
- `Assignment_Instructions_2.pdf`: Original assignment instructions.
- `Indian_Kids_Screen_Time.csv`: The raw dataset (9,712 records, 8 features).

---
*Course: Machine Learning, M.Sc. Data Science, HIT · Python, Pandas, NumPy, Scikit-learn, XGBoost, SHAP*
