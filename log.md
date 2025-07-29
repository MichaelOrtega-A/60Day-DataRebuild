## Day 44 – Tip Percentage Regression Modeling

**Objective:**  
Predict the `tip_pct` (tip percentage) using regression techniques and evaluate model performance.

---

### 🔨 Feature Engineering:
- Created interaction feature: `bill_size_interaction = total_bill * size`
- One-hot encoded categorical combo: `sex_time`
- Final feature set included:
  - `total_bill`, `size`, `bill_size_interaction`
  - `is_dinner`, `is_female`
  - One-hot encoded `sex_time` columns

---

### 🧠 Models Used:
1. **Linear Regression**
2. **Random Forest Regressor**

---

### 📊 Model Evaluation (Metrics):
| Model                   | MAE   | RMSE  | R²     |
|------------------------|-------|-------|--------|
| Linear Regression      | 0.5332| 0.7456| 0.5758 |
| Random Forest Regressor| 0.3274| 0.5051| 0.8053 |

---

### ✅ Insights:
- Random Forest significantly outperformed Linear Regression across all metrics.
- Shows strong ability to capture nonlinear patterns in the data.
- R² score of ~0.8053 indicates the model explains over 80% of the variance in tip percentage.

---

**Next Steps:**  
Explore hyperparameter tuning or alternative regressors like Gradient Boosting.
