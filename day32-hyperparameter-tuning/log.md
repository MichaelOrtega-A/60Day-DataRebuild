# 🧠 Day 32: Hyperparameter Tuning with GridSearchCV

### ✅ Objective:
Fine-tune the Support Vector Machine model using GridSearchCV with cross-validation to improve performance.

### 🔍 Grid Search Setup:
- **Parameter Grid:** 
  - `C`: [0.1, 1, 10]
  - `gamma`: [0.01, 0.1, 1]
  - `kernel`: ['rbf']
- **Cross-validation:** 5-fold StratifiedKFold

### 📊 Results:
- **Best Parameters:** `C=1`, `gamma=0.1`, `kernel='rbf'`
- **Best Cross-Validated Accuracy:** 82.7%
- **Final Accuracy on Full Data:** 84.1%

### 📈 Classification Report Highlights:
- Class 1 Precision: **0.85**
- Class 1 Recall: **0.71**
- Overall Accuracy: **0.84**

