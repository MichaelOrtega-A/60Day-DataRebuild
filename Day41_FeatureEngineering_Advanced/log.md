## Day 41 - Feature Engineering & Logistic Regression

### Dataset
- Used the built-in `tips` dataset from seaborn.

### Feature Engineering
- Created `tip_pct` (tip percentage).
- Binned `tip_pct` into `tip_level` with categories: `Low`, `Medium`, `High`.
- Created interaction term: `bill_size_interaction = total_bill * size`.
- Combined `sex` and `time` into one categorical feature: `sex_time`.
- Applied one-hot encoding on `sex_time`.
- Dropped irrelevant columns: `smoker`, `day`.

### Model Training
- Used `LogisticRegression` to predict `tip_level`.
- Trained on features:
  - `total_bill`, `tip`, `size`, `bill_size_interaction`
  - plus dummy variables from `sex_time`
- Encoded target labels using `LabelEncoder`.

### Model Saving
- Saved trained model, label encoder, and feature list using `joblib`.

### Prediction
- Created new sample input.
- Engineered the same features used in training.
- Ensured alignment with training feature order.
- Loaded the model and predicted `tip_level`.
