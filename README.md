Customer Churn Prediction using Machine Learning

 Project Overview
Customer churn prediction is one of the most important applications of machine learning in the telecom industry. This project predicts whether a customer is likely to leave the telecom service based on customer demographics, account information, and subscribed services.

 Objectives
- Perform Exploratory Data Analysis (EDA)
- Handle data preprocessing
- Perform feature engineering
- Train multiple Machine Learning models
- Compare model performance
- Optimize models using GridSearchCV
- Evaluate models using ROC-AUC
- Explain predictions using SHAP values

 Dataset
Dataset: IBM Telco Customer Churn Dataset

Target Variable:
- Churn
  - 0 = No Churn
  - 1 = Churn

 Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- SHAP

 Machine Learning Models

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

 Model Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- Cross Validation

 Feature Engineering

Three new features were created:

- LongTermCustomer
- HighMonthlyCharges
- AverageMonthlySpend

These engineered features improved model understanding and prediction capability.

 Explainable AI

SHAP (SHapley Additive Explanations) was used to explain the importance of individual features and improve model interpretability.

 Project Structure

Customer_Churn_Prediction/

├── Customer_Churn_Prediction.ipynb

├── Telco-Customer-Churn.csv

├── Customer_Churn_Report.pdf

├── Customer_Churn_Presentation.pptx

├── README.md

└── requirements.txt

 How to Run

1. Clone the repository.
2. Install required libraries.
3. Open the notebook in Google Colab or Jupyter Notebook.
4. Run all cells sequentially.

 Results

Models compared:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

The models were evaluated using Accuracy, Precision, Recall, F1-Score, ROC Curve, Cross Validation, GridSearchCV, and SHAP Explainability.


Shruthi Rathod
B.Tech CSD
IIIT Nagpur
