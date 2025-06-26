# Day 16 – Overfitting & Decision Tree Visualization

**🧠 Focus:**  
- Understanding overfitting through decision trees  
- Visualizing model behavior using `plot_tree` from `sklearn`  

**📊 What I Did:**  
- Trained a fully-grown Decision Tree (no max_depth limit)  
- Compared it with a regular/pruned tree using max_depth=4  
- Observed that:
  - **Overfit Tree** → Training Accuracy: 98.03% | Test Accuracy: 78.21%  
  - **Regular Tree** → Training Accuracy: ~82% | Test Accuracy: ~80%  

**🔍 What I Learned:**  
- Overfitting happens when the model memorizes the training data too closely, failing to generalize to unseen data  
- High training accuracy and much lower test accuracy is a key red flag  
- Visualizing tree splits helped me see how complexity can hurt generalization  
- I’m gaining confidence in recognizing when a model is "too good to be true"  

**✅ Why This Matters:**  
This is a major milestone in learning to *trust but verify* my models.  
It’s not just about accuracy — it’s about performance on real-world, unseen data.

---

