# Day 19: Limited Leaf Decision Tree

## ✅ What I did
- Trained a Decision Tree with `max_leaf_nodes=10` to prevent overfitting
- Compared performance against baseline (fully grown) tree
- Visualized final model using `plot_tree()`

## 📊 Results
- **Baseline Tree → Training Accuracy:** 98.03 %  
- **Baseline Tree → Test Accuracy:** 78.21 %  
- **Tuned Tree (10 leaves) → Training Accuracy:** 84.65 %  
- **Tuned Tree → Test Accuracy:** 79.53 %

## 💡 Notes
- Reducing `max_leaf_nodes` decreased overfitting
- Model generalizes better with slightly lower training accuracy but improved test accuracy
- Visualizations show a clearer, more interpretable structure

