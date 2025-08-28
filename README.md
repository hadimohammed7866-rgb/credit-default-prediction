## 📌 Project Overview
This project focuses on predicting the likelihood of credit card default using **Machine Learning algorithms** and **Neural Networks**. The aim is to improve credit risk assessment for financial institutions by analyzing customer demographics, payment history, and financial behavior.

## 🗂 Dataset
- **Source:** [UCI Credit Card Default Dataset](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)
- **Size:** 30,000 clients with 24 features
- **Target Variable:** Default payment (Yes/No)

## ⚙️ Methods Used
- Logistic Regression  
- SVM
- Random Forest  
- Gradient Boosting (XGBoost / LightGBM)  
- MLP

## 📊 Results
- Models evaluated using **Accuracy, Precision, Recall, F1-Score, and ROC-AUC**.  
- Feature importance analysis revealed payment history and credit limit as key factors.

## 🚀 How to Run
Clone this repository and install dependencies:

```bash
git clone https://github.com/yourusername/credit-default-prediction.git
cd credit-default-prediction
pip install -r requirements.txt
