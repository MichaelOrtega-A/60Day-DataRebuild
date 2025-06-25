# ✅ Day 15 Log – Cross-Validation Clarity

Today I finally wrapped my head around what cross-validation really means.  
The analogy comparing model training to studying for a test helped me see why we split data and how it prevents overfitting.  
It’s not just about accuracy — it’s about building models that actually *generalize* to new, unseen data.

I practiced using `cross_val_score()` with Logistic Regression and Random Forest,  
and saw how results like `[0.80, 0.82, 0.78, 0.79, 0.81]` give a more complete picture than a single train/test split.  
I also learned how scaling features (like with `StandardScaler`) is critical for models like Logistic Regression.

I feel like I’m learning how to think like a real data scientist, not just code like one.

Tomorrow, I’ll keep pushing forward — understanding one more layer at a time.
