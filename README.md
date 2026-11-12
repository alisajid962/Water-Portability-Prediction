# Water-Portability-Prediction
# 💧 Water Quality Prediction & Machine Learning System

An end-to-end machine learning project to predict water potability (`water_potability.csv`) with rigorous preprocessing, model comparison, and deployment readiness.

## 🔗 Repository Link
View the complete source code and project files in the [GitHub Repository](https://github.com/alisajid962/Water-Portability-Prediction.git)[cite: 3].

---

## 🚀 Key Features & Workflow
- **Leakage-Free Preprocessing**: Handled missing values using `KNNImputer` and applied Z-Score normalization (`StandardScaler`) strictly on the training set.
- **Model Evaluation & Comparison**: Evaluated Logistic Regression, Decision Trees, XGBoost, and a Soft Voting Ensemble using 5-fold cross-validation.
- **Overfitting Prevention**: Regularized tree depth (`max_depth=12`) and leaf sizes (`min_samples_leaf=4`) to ensure reliable generalization (~65.4% test accuracy) without risking dangerous false-safe predictions.
- **Interactive Application**: Integrated with a Streamlit interface for live water sample prediction and simulation.

---

## 📊 Model Performance Summary

| Model Name | Test Accuracy | ROC-AUC |
| :--- | :---: | :---: |
| Logistic Regression | 60.9%[cite: 3] | 0.544[cite: 3] |
| Decision Tree | 62.2%[cite: 3] | 0.612[cite: 3] |
| XGBoost / Gradient Boosting | 64.5%[cite: 3] | 0.649[cite: 3] |
| **Voting Ensemble (RF + Extra Trees)** | **65.4%**[cite: 3] | **0.674**[cite: 3] |

---

## ⚙️ Quick Start
1. Clone the repository:
   ```bash
   git clone [https://github.com/alisajid962/Water-Portability-Prediction.git](https://github.com/alisajid962/Water-Portability-Prediction.git)
