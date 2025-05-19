# 🏦 Loan Eligibility Prediction App

> Predict whether a loan application will be approved using Machine Learning — powered by Streamlit.

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Status](https://img.shields.io/badge/status-deployed-brightgreen.svg)
![Made with ML](https://img.shields.io/badge/Machine%20Learning-Sklearn-orange)

🚀 **Live App**:  
👉 [Try it on Streamlit](https://loanpredection-anbyswd5wrgwrjtge4hwa8.streamlit.app/)

---

## 📌 Project Overview

This project predicts loan approval based on applicant details using logistic regression and other ML models. It includes:

- 📊 Exploratory Data Analysis (EDA)
- 🧹 Data Cleaning & Encoding
- 🤖 Model Training (Logistic Regression, Decision Tree, etc.)
- ✅ Evaluation Metrics
- 🌐 Interactive Streamlit Web App

---

## 🔍 How It Works

1. User inputs data (income, loan amount, credit history, etc.)
2. Model predicts **Loan Status** (Approved or Not)
3. Visual outputs & results displayed instantly

---

## ⚙️ Tech Stack

| Tool           | Description                         |
|----------------|-------------------------------------|
| Python         | Core programming language           |
| Pandas, NumPy  | Data manipulation                   |
| Matplotlib, Seaborn | Visualizations                 |
| Scikit-learn   | ML model training and evaluation    |
| Streamlit      | Web app deployment                  |
## 📊 Sample Features

| Feature         | Description                        |
|----------------|------------------------------------|
| Gender          | Male/Female                        |
| Married         | Yes/No                             |
| ApplicantIncome | Numeric (Monthly Income)           |
| LoanAmount      | Numeric                            |
| Credit_History  | Binary (0 or 1)                    |

---

## 🧪 Running Locally

```bash
# Clone the repo
git clone https://github.com/yourusername/loan-eligibility-prediction.git
cd loan-eligibility-prediction

# Install dependencies
pip install -r requirements.txt

# Run Streamlit app
streamlit run app.py


## Example Prediction Output

✔️ Prediction: Loan Approved
📉 Probability: 85.3%
