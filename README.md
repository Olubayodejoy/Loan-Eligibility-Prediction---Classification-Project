# Loan-Eligibility-Prediction---Classification-Project
This machine learning model predicts whether a loan should be approved based on historical application data.
This project predicts whether an applicant is eligible for a loan based on personal and financial information. It uses a classification model trained on a dataset with various applicant features.

---

## 📊 Problem Statement

Financial institutions receive thousands of loan applications. Automating the loan eligibility decision process helps save time and improves consistency. This machine learning model predicts whether a loan should be approved based on historical application data.

---

## 🧾 Dataset Features

The dataset includes the following features:

- `Loan_ID`: Unique loan application ID
- `Gender`: Male / Female
- `Married`: Yes / No
- `Dependents`: Number of dependents
- `Education`: Graduate / Not Graduate
- `Self_Employed`: Yes / No
- `ApplicantIncome`: Income of the applicant
- `CoapplicantIncome`: Income of the coapplicant
- `LoanAmount`: Loan amount requested
- `Loan_Amount_Term`: Loan duration (in days)
- `Credit_History`: Credit score history (1 = good, 0 = bad)
- `Property_Area`: Urban / Semiurban / Rural
- `Loan_Status`: Target variable (Y = eligible, N = not eligible)

---

## 🔧 Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔍 Project Workflow

- Loaded and cleaned the dataset  
- Handled missing values and encoded categorical variables  
- Performed Exploratory Data Analysis (EDA) to understand patterns and correlations  
- Trained classification models (Logistic Regression, DecisionTreeClassifier, RandomForestClassifier, XGBClassifier)  
- Evaluated model using accuracy score and confusion matrix

---

## 📈 Model Performance

- Best Model: LogisticRegression 
- Accuracy: 84.55%  
