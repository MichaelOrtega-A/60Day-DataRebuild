# Day 11 Log – Random Forest GridSearch

Today I learned how to fine-tune a machine learning model using `GridSearchCV`.

I created a hyperparameter grid to test:
- n_estimators: [50, 100, 200]
- max_depth: [None, 5, 10]
- min_samples_split: [2, 5]

After running GridSearchCV with cross-validation, my best combo was:
`{'max_depth': None, 'min_samples_split': 5, 'n_estimators': 100}`  
With a cross-validated accuracy of **82.83%**

I now understand that tuning a model is like adjusting all the dials to get the best version possible — and GridSearch tries every combination until it finds the top one.

This was my favorite day so far — I actually understood what was happening, and it clicked 🔥
