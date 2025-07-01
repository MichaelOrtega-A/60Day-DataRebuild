### Day 20: Random Forest Depth Tuning

**Objective:**  
Investigated how `max_depth` impacts the performance of a Random Forest classifier on the Titanic dataset.

**What I Did:**
- Trained multiple Random Forest models with varying `max_depth` values: `[3, 5, 7, 9, 11, None]`
- Recorded training and test accuracy for each depth
- Visualized the trade-off between underfitting and overfitting using a line chart

**Findings:**
- Training accuracy steadily increased with tree depth, reaching 98% at no limit
- Test accuracy peaked at around **depth 5 or 7**, then plateaued or slightly dropped
- Clear sign of **overfitting** at deeper trees: high training accuracy but lower generalization

**Accuracy Summary:**
```
Max Depth: 3     → Train: 83.43%  | Test: 81.01%
Max Depth: 5     → Train: 85.39%  | Test: 82.68%
Max Depth: 7     → Train: 89.47%  | Test: 80.45%
Max Depth: 9     → Train: 93.12%  | Test: 82.68%
Max Depth: 11    → Train: 95.79%  | Test: 82.12%
Max Depth: None  → Train: 98.03%  | Test: 81.01%
```

**Reflection:**
Controlling model complexity is key. Limiting depth helped avoid overfitting and improved test performance. Learned how Random Forest behaves similarly to Decision Trees with respect to depth but tends to generalize a bit better.

---
