# 🧠 Day 27: Feature Selection

### ✅ Objectives:
- Identify and remove irrelevant/redundant features
- Use correlation heatmap and Random Forest for feature ranking

### 🔍 Key Findings:
- `Sex_male` was the most important feature (~0.26)
- `Fare`, `Age`, and `Pclass` also contributed significantly
- `PassengerId` showed high importance but is **not a valid feature** — dropped
- `SibSp` and `Parch` may be redundant; consider combining into `FamilySize`
- `Embarked` dummy variables had low impact

### ✅ Action Taken:
- Dropped `PassengerId`
- Reassessed categorical and numerical features
- Created bar plot for model-based importance using Random Forest

### 📁 Notebook: `day27-feature-selection.ipynb`
