# 📅 Day 21: Feature Importance Comparison

## 🎯 Objective
Compare how **Random Forest** and **Logistic Regression** interpret and rank feature importance on the Titanic dataset.

## 🔍 Models Used
- Random Forest Classifier
- Logistic Regression

## 📊 Results

### 🔹 Random Forest Feature Importance
| Feature      | Importance |
|--------------|------------|
| Fare         | High       |
| Sex          | High       |
| Age          | High       |
| Pclass       | Moderate   |
| FamilySize   | Low        |
| Embarked     | Very Low   |
| IsAlone      | Very Low   |

- Decision-based model — uses splits based on data patterns.
- Heavily favors continuous variables (e.g. **Fare**, **Age**) and categorical splits like **Sex**.

### 🔸 Logistic Regression Coefficients
| Feature      | Coefficient | Effect on Survival |
|--------------|-------------|--------------------|
| Sex          | Positive    | Increased chance   |
| Embarked     | Positive    | Slight increase    |
| Fare         | Positive    | Slight increase    |
| IsAlone      | Negative    | Decreased chance   |
| Age          | Negative    | Decreased chance   |
| FamilySize   | Negative    | Decreased chance   |
| Pclass       | Negative    | Lower class ↓ odds |

- Coefficients show direction of influence.
- **Sex** is a strong positive indicator for survival.
- **Pclass** and **Age** negatively impact survival odds.

## 🧠 Takeaways
- Both models agree that **Sex** is the most predictive feature.
- Random Forest picks up nonlinear patterns and interactions (e.g. Fare).
- Logistic Regression is more interpretable due to coefficient direction.

---

