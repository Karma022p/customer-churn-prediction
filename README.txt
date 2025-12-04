# 📊 Customer Churn Prediction – Machine Learning Project

Predicting customer churn helps businesses identify customers at risk of leaving so they can take early action.  
This project uses the Telco Customer Churn dataset to build multiple ML models, compare their performance, and extract key churn insights.

<p align="center">
  <img src="visuals/model_comparison.png" width="600">
</p>

---

## ⭐ Project Highlights

✔ Complete end-to-end machine learning workflow  
✔ Data cleaning, EDA, feature engineering, model building  
✔ Advanced ML models (Decision Tree, Random Forest, Gradient Boosting)  
✔ Hyperparameter tuning using GridSearchCV & RandomizedSearchCV  
✔ Feature importance insights for business decisions  
✔ Professional repository structure & documentation  

---

## 🧭 Workflow Overview

1. **Data Cleaning**  
2. **Exploratory Data Analysis (EDA)**  
3. **Feature Engineering**  
4. **Baseline Logistic Regression Model**  
5. **Advanced Models**  
   - Decision Tree  
   - Random Forest  
   - Gradient Boosting  
6. **Hyperparameter Tuning & Cross-Validation**  
7. **Model Performance Comparison**  
8. **Feature Importance & Insights**

---

## 🧠 Best Performing Model

### 🥇 **Random Forest (Tuned)**  
This model achieved the **highest AUC score**, making it the best at identifying which customers are likely to churn.

---

## 📈 Model Performance Comparison

<p align="center">
  <img src="visuals/model_comparison.png" width="600">
</p>

---

## 🔍 Feature Importance

<p align="center">
  <img src="visuals/feature_importance.png" width="500">
</p>

### **Top Drivers of Customer Churn**

1. Tenure  
2. Total Charges  
3. Fiber Optic Internet Service  
4. Monthly Charges  
5. Electronic Check Payment  

---

## 💡 Key Insights

- Customers with **short-term contracts** are more likely to churn.  
- **Low-tenure customers** need special onboarding attention.  
- **Fiber optic users** churn more, suggesting potential service issues.  
- **Higher monthly charges** increase churn probability.  
- Customers using **electronic checks** churn at higher rates.

These insights can help companies improve their retention strategy and reduce churn.

---

## 🛠 Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📚 Dataset

This project uses the **Telco Customer Churn** dataset which includes customer information such as contracts, charges, internet services, and churn status.

---

## ⭐ How to Run This Project

```bash
pip install -r requirements.txt   # optional if you create one

jupyter notebook
