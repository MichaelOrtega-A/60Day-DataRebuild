# Day 10 Log – Cross-Validation & Model Evaluation

**🧠 What I did:**
- Compared Logistic Regression vs. Random Forest using cross-validation (`cross_val_score`)
- Scaled features using `StandardScaler` for logistic regression
- Evaluated performance across 5 folds instead of a single test split
- Learned how feature scaling impacts different models

**📚 What I learned:**
- Cross-validation gives a more trustworthy performance score than one train/test split
- Logistic Regression relies on feature weights — scaling helps balance those weights
- Random Forest doesn’t need scaling since it splits on values instead of weighting them
- Even binary features like `Sex` (0/1) get scaled to have mean 0 and std 1

**📈 Results:**
- Logistic Regression CV Accuracy: ~[your % here]%
- Random Forest CV Accuracy: ~[your % here]%
- Random Forest slightly outperformed Logistic Regression

**✅ Wins:**
- Understood the math behind why scaling matters
- Realized how models “see” features with large values like `Fare`
- Got more comfortable evaluating models the right way

**🔁 Next:**
- Try other models later (KNN, SVM)
- Practice encoding additional features like `Title`
- Prepare for model tuning (e.g., hyperparameters)

**🔥 Mindset Check:**
Things are clicking more. It feels good to know I’m not just coding, but understanding. This is starting to feel like real progress.
