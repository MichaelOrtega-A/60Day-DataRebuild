### 📅 Day 26: Feature Selection using SelectKBest (ANOVA F-test)

🔍 Objective:
Use SelectKBest with ANOVA F-test to rank features based on their linear relationship to the survival outcome.

⚙️ Steps:
- Loaded the Titanic dataset and prepared features/target.
- Applied SelectKBest(score_func=f_classif) to calculate F-scores for all features.
- Sorted and visualized feature scores using Seaborn barplot.

📊 Top Features:
| Feature     | F-score |
|-------------|---------|
| Sex         | 372.41  |
| Pclass      | 115.03  |
| Fare        |  63.03  |
| IsAlone     |  38.35  |
| Embarked    |  10.26  |

🧠 Insights:
- Sex, Pclass, and Fare continue to rank high — reaffirming earlier findings.
- SelectKBest is useful when you want a quick ranking of features based on linear dependency with the target.
- Lower-ranking features like PassengerId and FamilySize showed minimal impact and could be dropped in future modeling.
