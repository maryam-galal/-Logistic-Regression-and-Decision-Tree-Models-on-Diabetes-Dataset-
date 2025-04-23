## Logistic Regression for Binary Classification – Project Summary

This project applies **Logistic Regression**, **Decision Tree**, and **Random Forest** models on the **Pima Indians Diabetes Dataset** using a complete machine learning pipeline. Various experiments were conducted to evaluate model performance under different preprocessing and tuning conditions using `GridSearchCV`.

### ✅ Models & Methodology
- Models Used:
  - Logistic Regression (with L1 & L2 regularization)
  - Decision Tree Classifier
  - Random Forest Classifier
- Preprocessing Techniques:
  - Feature Scaling using `StandardScaler`
  - Handling class imbalance with OverSampling and SMOTE
- Hyperparameter Tuning:
  - Implemented using `GridSearchCV`
- Evaluation Metrics:
  - Accuracy, Precision, Recall, F1-score, Confusion Matrix

### 🔬 Experiments Conducted
1. **Baseline Model Training (70/30 split)**  
2. **Feature Scaling**: Performance improved slightly for Logistic Regression.  
3. **Train-Test Split Change (80/20)**: Showed marginal changes; models were consistent.  
4. **Regularization**:
   - **L1 (Lasso)**: Helped reduce less important features.
   - **L2 (Ridge)**: Generally produced slightly more stable models.
5. **Sampling Techniques**:
   - OverSampling and SMOTE significantly improved performance for imbalanced classes.

### 🥇 Best Performing Model
After tuning and preprocessing, **Random Forest with GridSearchCV and SMOTE** gave the best performance overall in terms of **F1-score** and **balanced accuracy**.

### ⚙️ Challenges Faced
- Balancing the dataset without overfitting.
- Choosing optimal hyperparameters.
- Interpretation of regularization effects on model complexity.

### 📚 Key Learnings
- Feature scaling is critical for gradient-based models like Logistic Regression.
- SMOTE is highly effective in improving recall for the minority class.
- Regularization helps control overfitting and model complexity.
- Decision Trees and Random Forests are robust to unscaled features and imbalanced data.

---

> 🎓 Dataset Source: [Pima Indians Diabetes Database on Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

> 📄 Deliverables include: `.ipynb` notebook, this `README.md`, and visualizations.

---

