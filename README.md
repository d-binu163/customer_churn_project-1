# 📊 Customer Churn Prediction

This project predicts customer churn for a telecommunications company using machine learning. It explores key drivers behind customer retention and builds a logistic regression model to classify whether a customer is likely to leave.

---

## 🧠 Objective

To analyze telecom customer behavior and develop a model that can predict whether a customer will churn. The goal is to help the business proactively retain customers by identifying high-risk segments.

---

## 📁 Project Structure

.

├── notebook/

│ └── customer_churn_project1.ipynb

├── data/

│ └── WA_Fn-UseC_-Telco-Customer-Churn.xls

├── README.md

└── requirements.txt


---

## 🧰 Tools and Libraries

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Imblearn

---

## 📊 Dataset

**Features include**:
- Demographics (gender, senior citizen)
- Services (InternetService, PhoneService)
- Account details (Contract, PaymentMethod)
- Target variable: `Churn` (Yes/No)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer_churn_project.git
   cd customer_churn_project


## Modeling Approach

- Baseline model: Logistic Regression, DecisionTrees, KNearestNeighbours, Logistic using SMOTE

- Preprocessing:

    - Handled missing values

    -   Encoded categorical variables

    -   Scaled numerical features

- Evaluation metrics:

    -   Accuracy

    -   Confusion matrix

    -   Classification report


## Results Summary

- Logistic regression identified Contract type, OnlineSecurity, and TechSupport as key predictors of churn.

- Customers with month-to-month contracts and no added services were more likely to churn.

- Although Logistic is simple and interpretable, its performance may be limited for more complex relationships in the data. 


## License

This project is licensed under the MIT License.
This project is for educational and non-commercial use only.
