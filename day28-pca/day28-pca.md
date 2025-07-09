# 🧠 Day 28: Dimensionality Reduction with PCA

### ✅ Objectives:
- Reduce dataset dimensionality while preserving important variance
- Visualize explained variance by principal components
- Improve model performance and interpretability

### 🔍 Key Steps:
- Cleaned and encoded Titanic dataset
- Scaled features using `StandardScaler`
- Applied PCA with `n_components=0.95`
- Reduced from 8 features → 7 principal components
- Plotted cumulative explained variance

### 📊 Insights:
- PCA retained ~95% of dataset variance with just 7 components
- This helps speed up training and reduces noise
- Explained variance plot showed diminishing returns after 5-6 components


