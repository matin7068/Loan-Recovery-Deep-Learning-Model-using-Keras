# Loan Default Prediction with Keras


## 📌 Project Overview
This project builds a neural network model using **Keras** to predict whether a borrower will fully repay their loan or default (charged off), based on historical LendingClub data.

The dataset includes borrower details such as loan amount, interest rate, employment length, annual income, credit history, and more.  
Our goal: **Classify new loan applications as likely to be repaid or defaulted**, to help lenders make informed decisions.

---

## 📊 Dataset
- **Source:** LendingClub dataset (special processed version provided by [Pierian Data Inc.](https://www.pieriandata.com))
- **Original Data Credits:** Copyright © Pierian Data Inc., Created by Jose Marcial Portilla
- **Kaggle reference:** [Lending Club Loan Data](https://www.kaggle.com/wordsforthewise/lending-club) *(full dataset differs from the one used here)*

**Target variable:**  
- `loan_status` — indicates if the loan is "Fully Paid" or "Charged Off"

**Example features:**
- `loan_amnt` – loan amount requested
- `term` – repayment term (36 or 60 months)
- `int_rate` – interest rate
- `installment` – monthly payment
- `grade` / `sub_grade` – LendingClub credit grades
- `emp_length` – employment length
- `home_ownership` – Rent / Own / Mortgage
- `annual_inc` – annual income
- `mort_acc` – number of mortgage accounts
- `pub_rec_bankruptcies` – bankruptcies on record

---

## 🛠️ Tech Stack
- **Python**
- **Keras** / TensorFlow
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

---

## 📈 Workflow
1. **Data Loading** – Load and explore the dataset.
2. **Data Cleaning** – Handle missing values, encode categorical variables, feature engineering.
3. **Exploratory Data Analysis (EDA)** – Visualize distributions, correlations, and relationships.
4. **Preprocessing** – Train-test split, scaling features.
5. **Model Building** – Define and compile a Keras Sequential model.
6. **Model Training** – Train using training data with appropriate metrics.
7. **Evaluation** – Assess model performance on test data using classification metrics.
8. **Predictions** – Use the trained model to predict new loan applications.

---

## 🚀 How to Run
```bash
# Clone this repository
git clone https://github.com/yourusername/loan-default-prediction.git

# Navigate to the folder
cd loan-default-prediction

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook 04-Keras-Project-Exercise-Solutions.ipynb
