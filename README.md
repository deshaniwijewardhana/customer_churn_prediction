# Customer Churn Prediction

This project predicts customer churn in a telecom company using machine learning. Customer demographics, service usage, and billing data were analyzed, and Logistic Regression and Random Forest models were used to identify customers likely to leave the service.

---

## Project Overview

Customer churn is a critical problem for subscription-based businesses such as telecom companies. This project aims to predict whether a customer will churn (leave the service) based on demographic information, account details, and service usage patterns using machine learning techniques.

---

## Dataset

- **Source:** [Telco Customer Churn Dataset (Kaggle)](https://www.kaggle.com/code/danishmubashar/telco-customer-churn-97-acc)  
- **Records:** ~7,000 customers  
- **Target Variable:** `Churn` (Yes / No)

---

## Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook

---

## Methodology

1. Data loading and inspection  
2. Data cleaning and handling missing values  
3. Exploratory Data Analysis (EDA)  
4. Feature encoding and scaling  
5. Model training using:
   - Logistic Regression  
   - Random Forest Classifier  
6. Model evaluation using:
   - Accuracy  
   - Precision, Recall, F1-score  
   - Confusion Matrix  
   - ROC-AUC score

---

## Results

- Random Forest outperformed Logistic Regression.  
- Customers with short tenure and high monthly charges showed a higher probability of churn.

---

## Conclusion

The developed model can help telecom companies identify high-risk customers early and take proactive steps to improve customer retention.

---
## How to Run

You can **run this project directly in Google Colab**:

[[![Open In Colab](](https://colab.research.google.com/drive/1gG6d5BPnf-gaSyfJl-q2NjUTSStKvUtg)

2. **Using Jupyter Notebook locally:**
   - Clone the repository
   - Navigate into the project folder
   - Install required packages
   - Open `customer_churn_prediction.ipynb` in Jupyter Notebook and run all cells

## Contribution

- Deshani Wijewardhana (Individual Project)
