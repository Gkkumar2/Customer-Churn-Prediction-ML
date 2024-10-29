# 📊 Customer Churn Prediction

![Python](https://img.shields.io/badge/Python-3.8-blue?style=flat-square&logo=python) 
![scikit-learn](https://img.shields.io/badge/scikit--learn-0.24-orange?style=flat-square&logo=scikit-learn)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

Predict customer churn using a **Random Forest Classifier** on customer account data, achieving insights into potential churn behaviors.

---

## Project Summary
- **Objective**: Classify customers as likely to churn or stay.
- **Dataset**: Customer information such as demographics and account details.
- **Model**: Random Forest Classifier with an accuracy of **85.7%**.
- **Results**: Successfully predicts churn with balanced precision and recall metrics.

---

## Process Overview

1. **Data Preprocessing** 🧹
   - Converted categorical features with **One-Hot Encoding**.
   - **Standardized** numerical columns to enhance model performance.

2. **Modeling** 🚀
   - Split data into 85% training and 15% test sets.
   - Trained a **Random Forest Classifier** with 100 estimators.

3. **Evaluation** 📈
   - **Accuracy**: 85.7%
   - **Confusion Matrix**:
     ```
     [[1158   36]
      [ 178  128]]
     ```

---

## Visual Insights

- **Customer Geography**:  
  ![France](https://img.shields.io/badge/-France%2050.1%25-orange?style=flat-square) 
  ![Germany](https://img.shields.io/badge/-Germany%2025.1%25-blue?style=flat-square)
  ![Spain](https://img.shields.io/badge/-Spain%2024.8%25-green?style=flat-square)

- **Age Distribution Among Churners**  
  ![Age Distribution](https://www.example.com/age_distribution_chart.png)

- **Balance Distribution by Churn**  
  ![Balance Distribution](https://www.example.com/balance_distribution_chart.png)

---

## Features Used
- **CreditScore**
- **Age**
- **Balance**
- **NumOfProducts**
- **IsActiveMember**
- **EstimatedSalary**
- **Geography, Gender**

---

## Deployment
The model is saved using `pickle` for easy loading and deployment.

## License
This project is licensed under the MIT License.
