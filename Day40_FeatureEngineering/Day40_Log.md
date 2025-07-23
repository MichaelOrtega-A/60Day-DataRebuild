## 📅 Day 40 – Feature Engineering & Logistic Regression

### 🎯 Objective
Prepare and transform the **Tips** dataset for machine learning by engineering features, cleaning the data, and training a **Logistic Regression** model to predict whether a tip was generous (above 15%).

---

### 🛠️ What I Did
- Loaded the `tips` dataset using Seaborn.
- Created a new column `tip_pct` = (`tip` / `total_bill`) × 100.
- Rounded `tip_pct` to 2 decimal places.
- Dropped less informative columns: `smoker`, `day`.
- One-hot encoded categorical variables: `sex`, `time`.
- Scaled numeric features: `total_bill`, `tip`, `size`, `tip_pct` using `StandardScaler`.
- Created a binary target column `high_tip` → 1 if tip_pct > 15, else 0.
- Split the dataset into training/testing sets using `train_test_split` with `stratify`.
- Trained a **Logistic Regression** model.
- Evaluated model performance with:
  - ✅ Accuracy Score  
  - 📊 Confusion Matrix  
  - 🧾 Classification Report

---

### 🧠 Key Takeaways
- **Feature engineering** is about creating meaningful variables that make patterns easier for models to detect.
- **Scaling** is critical when using distance-based or weight-based models like Logistic Regression.
- **One-hot encoding** helps convert categorical data into numeric format while preserving meaning.
- Logistic Regression is a strong **baseline** model for binary classification tasks.
