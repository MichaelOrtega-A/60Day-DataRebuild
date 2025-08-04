Day 47: Scikit-learn Classification with Logistic Regression

🔄 Recap

In Day 46, we implemented logistic regression from scratch using NumPy. We manually coded the sigmoid function, loss calculation, gradient descent, and prediction pipeline. This gave us an in-depth understanding of the internal mechanics of classification models.

🌟 What's New Today

Today we transitioned from manual implementation to using scikit-learn, Python's most popular machine learning library. This shift introduces us to industry-standard tools for:

Fast experimentation

Built-in evaluation metrics

Reproducibility

We:

Imported and used LogisticRegression from sklearn.linear_model

Fit the model on training data and evaluated on test data

Computed Accuracy, Precision, Recall, F1 Score

Generated and visualized a confusion matrix using seaborn

✅ Key Results

Accuracy: 72%

Precision: 69.5%

Recall: 73.4%

F1 Score: 71.4%

The confusion matrix showed class imbalance in prediction errors.

🤖 Why This Matters

Using scikit-learn lets us:

Benchmark models faster

Focus on experimentation instead of boilerplate

Compare different classifiers later (like KNN, Decision Trees, etc.)

We now have both theoretical and practical foundations.

Next up: try different classifiers and hyperparameters!

💪 Wins

First classifier using sklearn

Plotted confusion matrix successfully

Got solid metrics to track future improvements

