## Day 45 – Metric Fixes & Regression Model Evaluation ✅

### ✅ What I Did
- Updated `evaluate_model()` to manually compute **RMSE** using `np.sqrt(mean_squared_error(...))` due to `scikit-learn` version compatibility issues.
- Trained and evaluated **Linear Regression** and **Random Forest Regressor** to predict `tip_pct`.

### 📊 Model Performance

| Model                  | MAE   | RMSE  | R²     |
|------------------------|-------|-------|--------|
| Linear Regression      | 2.54  | 3.58  | 0.849  |
| Random Forest Regressor| 1.78  | 3.06  | 0.889  |

### 🔍 Key Takeaways
- **Random Forest** outperformed Linear Regression on all metrics, with **lower error and higher explained variance**.
- Learned the importance of computing metrics manually when library parameters are unsupported.
- RMSE & MAE give different insights: RMSE penalizes large errors, MAE is more stable to outliers.
- High R² (~0.889) means the model explains nearly 89% of the variance in target—strong performance.

---

Next up: we can work on model tuning, trying Polynomial Regression, or exploring entirely new datasets. Just say the word 🚀
