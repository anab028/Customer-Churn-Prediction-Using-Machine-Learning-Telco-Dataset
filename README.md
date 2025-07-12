# Telco Customer Churn Prediction

This project aims to predict customer churn using various machine learning models based on the Telco Customer Churn dataset. It demonstrates a full data science pipeline from data exploration to model evaluation and comparison.

---

## 📌 Objective

To identify customers likely to cancel their subscription based on service usage patterns, demographics, and account information. This helps businesses take proactive retention actions.

---

## 📁 Dataset

- **Source**: [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)
- 7043 rows, 21 columns
- Target: `Churn` (Yes/No)

---

## ⚙️ Workflow

1. Data Cleaning & Preparation
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Data Preprocessing (One-hot encoding, scaling)
5. Model Training:
   - Random Forest
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - XGBoost
6. Model Evaluation:
   - Accuracy, Precision, Recall, F1-Score
   - ROC-AUC comparison
   - Visualization

---

## 📊 Results

| Model               | Accuracy |
|--------------------|----------|
| Random Forest       | **0.8019** |
| Logistic Regression | 0.7842   |
| XGBoost             | 0.7849   |
| KNN                 | 0.7338   |

**🔹 Random Forest outperformed all other models in overall accuracy.**

---

## 📦 Technologies Used

- Python (pandas, NumPy, scikit-learn, matplotlib, seaborn, XGBoost)
- Jupyter/Google Colab
- Machine Learning Classification Algorithms

---

## 💡 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Streamlit deployment
- Feature importance analysis

---

## 🧠 Author

**Ahanab Hafiz Anab**  
📫 [LinkedIn](https://www.linkedin.com/in/ahanab-hafiz-anab-a594ab306/)  
📧 anabhafiz028@gmail.com
