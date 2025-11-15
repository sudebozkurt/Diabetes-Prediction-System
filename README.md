# Diabetes Data Processing and Machine Learning

This project focuses on predicting diabetes using extensive data preprocessing, exploratory data analysis (EDA), feature engineering, and multiple machine learning models. The implemented models include Logistic Regression, SVM, Random Forest, Decision Trees, Gradient Boosting, and Bayesian approaches. After evaluation, the best-performing models — Gradient Boosting and Random Forest — were selected.

---

## Model Performance Comparison

| Model               | Accuracy | Class 1 Recall | Class 1 F1 | Overfitting | Result     |
| ------------------- | -------- | -------------- | ---------- | ----------- | ---------- |
| Gradient Boosting   | 0.7338   | 0.59           | 0.61       | No          | ✔ Selected |
| Random Forest       | 0.7273   | 0.57           | 0.60       | No          | ✔ Selected |
| Decision Tree       | 0.69     | 0.54           | 0.55       | Yes         | ✘ Rejected |
| Logistic Regression | 0.71     | 0.50           | 0.55       | No          | ✘ Rejected |
| SVM                 | 0.71     | 0.48           | 0.54       | No          | ✘ Rejected |

**Conclusion:**  
- **Gradient Boosting** achieved the best overall metrics  
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
git clone https://github.com/sudebozkurt/Diabetes-Data-Processing-and-ML
cd Diabetes-Data-Processing-and-ML
pip install -r requirements.txt


