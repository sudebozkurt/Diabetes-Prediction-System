# Diabetes Data Processing and Machine Learning

This project focuses on predicting diabetes using extensive data preprocessing, exploratory data analysis (EDA), feature engineering, and multiple machine learning models. The implemented models include Logistic Regression, SVM, Random Forest, Decision Trees, Gradient Boosting, and Bayesian approaches. After evaluation, the best-performing models — Gradient Boosting and Random Forest — were selected.

---

## Model Performance Comparison

| Model               | Accuracy | Class 1 Recall | Class 1 F1 | Overfitting | Result     |
| ------------------- | -------- | -------------- | ---------- | ----------- | ---------- |
| Logistic Regression | 0.7600   | 0.75           | 0.69       | No          | ✔ Selected |
| Random Forest       | 0.7267   | 0.67           | 0.72       | No          | ✔ Selected |
| Gradient Boosting   | 0.7267   | 0.66           | 0.67       | No          | ✘ Rejected |
| SVM                 | 0.7467   | 0.67           | 0.69       | No          | ✘ Rejected |
| Decision Tree       | 0.7200   | 0.65           | 0.66       | Yes         | ✘ Rejected |

**Conclusion:**  
- **Logistic Regression** achieved the best overall metrics  
- **Random Forest** delivered balanced and reliable performance  

---

## Data Processing Steps

- Missing value analysis  
- Outlier detection  
- Standard scaling  
- Feature selection  
- Train-test split  
- Model training & evaluation  
- Hyperparameter tuning  
- Performance comparison and insights  

---
EDA & Visualizations

Included visual outputs:

- Correlation heatmap  
- Feature distributions  
- Class balance visualization  
- Model performance comparison charts  
- Confusion matrices

---
## Installation

Clone the repository:

```bash
git clone https://github.com/sudebozkurt/Diabetes-Prediction-System
cd Diabetes-Prediction-System
pip install -r requirements.txt
```

---
## Dataset Source

This project uses the *Pima Indians Diabetes Database* from Kaggle.

- Source: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database
- Original Provider: UCI Machine Learning Repository


