# CodeAlpha_Credit_Scoring_Model
Credit Scoring Model using Machine Learning with Python | CodeAlpha Machine Learning Internship Project

# 💳 Credit Scoring Model

## 📌 Project Overview

This project was developed as part of the **CodeAlpha Machine Learning Internship**.

The objective of this project is to build a **Credit Scoring Model** capable of predicting an individual's **creditworthiness** based on historical financial information using Machine Learning classification algorithms.

The project follows a complete Machine Learning workflow including **Data Understanding, Exploratory Data Analysis (EDA), Feature Engineering, Data Preprocessing, Model Building, Model Evaluation, Model Comparison, and Creditworthiness Prediction**.

---

# 🎯 Objective

Develop a Machine Learning model to predict whether a loan applicant has **good** or **poor** creditworthiness using historical financial data.

---

# 📂 Dataset

**Dataset Name:** German Credit Data Dataset

The dataset contains financial information of loan applicants, including:

- Checking Account
- Credit History
- Credit Amount
- Loan Duration
- Savings Account
- Employment Duration
- Age
- Housing
- Existing Credits
- Installment Rate
- Property
- Job
- Telephone
- Foreign Worker
- and several other financial attributes.

**Target Variable**

- **Credit_Risk**
  - 1 → Good Credit
  - 0 → Bad Credit

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab

---

# 📊 Exploratory Data Analysis (EDA)

Several visualizations were created to understand the dataset, including:

- Credit Risk Distribution
- Age Distribution
- Credit Amount Distribution
- Loan Duration Distribution
- Correlation Heatmap
- Credit Amount vs Credit Risk
- Age vs Credit Risk
- Loan Duration vs Credit Risk

These visualizations helped identify important trends and relationships within the dataset.

---

# ⚙️ Feature Engineering

To improve the predictive performance of the models, two additional financial features were created:

- **Monthly Loan Burden**
  - Credit Amount / Loan Duration

- **Credit per Existing Loan**
  - Credit Amount / (Existing Credits + 1)

These engineered features provide additional financial insights that help the models better understand repayment capacity and financial exposure.

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Renamed German column names to meaningful English names.
- Checked missing values.
- Removed duplicate records.
- Generated descriptive statistics.
- Selected input and target features.
- Split the dataset into training and testing sets.
- Applied feature scaling where required.

---

# 🤖 Machine Learning Models

Three classification algorithms were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

# 📈 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report

---

# 🏆 Best Performing Model

After comparing all models, **Random Forest Classifier** achieved the best overall performance and was selected as the final model for predicting creditworthiness.

---

# 🔮 Creditworthiness Prediction

The trained Random Forest model was used to predict the creditworthiness of a sample applicant.

Prediction Output:

- **Good Creditworthiness**
- **Poor Creditworthiness**

This demonstrates how Machine Learning can assist financial institutions in making informed lending decisions.

---

# 📁 Project Workflow

```
Import Libraries
        │
Load Dataset
        │
Rename Columns
        │
Data Understanding
        │
Exploratory Data Analysis
        │
Feature Engineering
        │
Data Preprocessing
        │
Train-Test Split
        │
Feature Scaling
        │
Model Building
        │
Model Evaluation
        │
Model Comparison
        │
Best Model Selection
        │
Creditworthiness Prediction
```

---

# 🚀 Future Improvements

- Perform Hyperparameter Tuning.
- Experiment with XGBoost and LightGBM.
- Handle class imbalance using SMOTE.
- Deploy the model using Streamlit or Flask.
- Build a real-time Credit Scoring Web Application.

---

# 📌 Conclusion

A complete Machine Learning pipeline was implemented to predict an individual's creditworthiness using historical financial data.

The project covered every stage of a real-world Machine Learning workflow, including data exploration, feature engineering, preprocessing, model development, evaluation, and prediction.

Among the three classification models, **Random Forest Classifier** produced the best overall performance and successfully predicted applicants' creditworthiness.

This project demonstrates how Machine Learning can support financial institutions in making faster, more accurate, and data-driven credit approval decisions.

---

# 👩‍💻 Author

**Kalpana**

---
Project completed as part of the **CodeAlpha Machine Learning Internship**.
