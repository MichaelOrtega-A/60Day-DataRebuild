## Day 18: Hyperparameter Tuning - Decision Tree Depth & Generalization

### ✅ What I Did:
- Practiced hyperparameter tuning with `max_depth` on Decision Trees using Titanic dataset.
- Compared performance between:
  - **Overfitted Tree** (no depth limit)
  - **Tuned Tree** (`max_depth=4`)
- Visualized both tree structures to observe impact of overfitting vs generalization.

### 📊 Results:
- **Overfitting Tree:**
  - Training Accuracy: 98.03 %
  - Test Accuracy: 78.21 %
- **Tuned Tree:**
  - Training Accuracy: 83.85 %
  - Test Accuracy: 79.89 %

### 🔍 Key Learnings:
- Overfitting captures noise in training data, leading to poor generalization.
- Simpler models (with max depth tuning) perform better on unseen data.
- Model interpretability improves when the tree is shallow and focused on meaningful features (e.g. `Sex`, `Pclass`, `Age`).

### 🛠️ Tools Used:
- `DecisionTreeClassifier` from `sklearn`
- `plot_tree` for visualization
- Matplotlib for tree plotting
