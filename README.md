# 🍷 Wine Classification Model Comparison

## 🚀 Overview
This project compares different dimensionality reduction techniques to evaluate their impact on classification performance.

We apply PCA, Kernel PCA, and LDA before training a Logistic Regression model on the Wine dataset.

---

## 📊 Dataset
- Wine dataset  
- Features: Chemical properties of wines  
- Target: Wine class  

---

## ⚙️ Approach
1. Train-test split  
2. Feature scaling (Standardization)  
3. Apply dimensionality reduction:
   - PCA
   - Kernel PCA (RBF kernel)
   - LDA
4. Train Logistic Regression  
5. Evaluate using confusion matrix and accuracy  

---

## 🧠 Techniques Compared

| Technique | Type | Key Idea |
|----------|------|---------|
| PCA | Unsupervised | Maximize variance |
| Kernel PCA | Unsupervised | Capture non-linear patterns |
| LDA | Supervised | Maximize class separation |

---

## 📊 Results Comparison

| Technique     | Performance |
|--------------|------------|
| PCA          | Slightly lower accuracy |
| Kernel PCA   | High accuracy (perfect classification) |
| LDA          | High accuracy (perfect classification) |

---

## 🏆 Best Performing Model
- **LDA and Kernel PCA performed the best**, achieving perfect classification.
- **PCA performed slightly worse** due to loss of discriminative information.

---

## 🧠 Key Insights
- LDA performs best because it uses class labels  
- Kernel PCA captures non-linear relationships effectively  
- PCA may lose important class-separating information  
- Dimensionality reduction can significantly impact model performance  

---

## 🎯 Conclusion
The choice of dimensionality reduction technique directly affects classification results.  
Supervised methods like LDA can outperform unsupervised ones when labels are available.

---

## 🔮 Future Improvements
- Add cross-validation  
- Compare with other classifiers  
- Visualize decision boundaries  
