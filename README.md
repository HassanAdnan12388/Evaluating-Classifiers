# Evaluating-Classifiers
Implementing and evaluating KNNS, Decision Trees and SVMs from scratch + libraries

## **Project Overview**
This project focuses on implementing and evaluating various **classification algorithms** from scratch and using libraries. 

---

## **Summary**
### **Tasks Covered**
1. **Data Preparation**
   - Load and visualize the dataset.
   - Split data into training and testing sets (80/20 split).
   
2. **Classification Models Implemented from Scratch**
   - **K-Nearest Neighbors (KNN)**
   - **Decision Tree Classifier**

3. **Classification Models Using Scikit-Learn**
   - **Support Vector Machines (SVMs)** with different kernels:
     - Linear Kernel
     - Polynomial Kernel
     - RBF Kernel

4. **Model Evaluation**
   - Accuracy, Precision, Recall, and F1-Score.
   - Confusion matrix heatmaps.
   - Decision boundary visualization.
   
5. **Hyperparameter Tuning**
   - Experimentation with different **K-values for KNN**.
   - Experimentation with **depth values for Decision Tree**.
   - Comparison of different **SVM kernels**.

---

## **Technologies Used**
- **Python**: Programming language for model implementation.
- **NumPy**: Numerical computations and matrix operations.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib & Seaborn**: Data visualization and plotting.
- **Scikit-Learn**: Library for implementing classification models.

---

## **Architecture**
1. **Dataset Preparation**
   - Load dataset using `pandas`.
   - Shuffle and split into training/testing sets.
   - Visualize data distribution.

2. **Custom Classification Models**
   - Implement KNN and Decision Tree classifiers from scratch.
   - Optimize hyperparameters.
   - Evaluate performance.

3. **Library-Based Models**
   - Train and evaluate SVM models with different kernels.
   - Compare performance with custom models.

4. **Model Evaluation & Visualization**
   - Generate confusion matrices.
   - Plot decision boundaries.
   - Compare accuracy of different approaches.


---

## **Key Features**
- **Hand-coded implementations** of KNN & Decision Tree.
- **Comparisons with Scikit-Learn models** (SVMs).
- **Decision boundary visualizations** for models.
- **Performance metrics analysis** with heatmaps.

---

## **Conclusion**
- KNN performs well but requires tuning of **K-value**.
- Decision Trees are prone to **overfitting** if depth is too high.
- SVM with **RBF and Polynomial kernels** performs best on this dataset.
- Model selection depends on **data distribution** and complexity.
```

