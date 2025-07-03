# Day 22: Permutation Feature Importance with Random Forest

## 🔍 Objective
Use permutation importance to better understand which features have the most impact on our Random Forest model's predictions.

## 🧠 Key Concept
- **Permutation Importance** measures how much model performance drops when a feature's values are randomly shuffled.
- A larger drop in accuracy = higher feature importance.

## ⚙️ Steps Taken
1. Trained a `RandomForestClassifier` on the Titanic dataset.
2. Computed permutation importance using `sklearn.inspection.permutation_importance`.
3. Converted results to a DataFrame and sorted features by importance.
4. Visualized results with a horizontal barplot using `seaborn`.

## 📊 Insights
- Features like **Fare**, **Sex**, and **Age** were the most influential according to permutation importance.
- Features with nearly zero importance may be redundant or uninformative.
