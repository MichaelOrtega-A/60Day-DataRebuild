# 🧠 Day 30: Model Evaluation with Cross-Validation

### ✅ Objectives:
- Evaluate model stability using K-Fold Cross-Validation
- Go beyond simple train/test splits
- Use metrics like precision, recall, F1-score, and confusion matrix

### 🔍 Results:
- **Cross-Validation Accuracies:** [0.8379, 0.8146, 0.7865, 0.8258, 0.8315]
- **Mean CV Accuracy:** 0.8193
- **Classification Report:**
  - Precision (Class 1): 0.78
  - Recall (Class 1): 0.74
  - F1-Score (Class 1): 0.76
- **Confusion Matrix** showed balanced prediction across classes

### 🧠 Interpretation:
- The model is **not overfitting** — performance is consistent across folds
- Cross-validation helps ensure the model will generalize to new, unseen data
- Precision/Recall/F1 give deeper insights than accuracy alone

