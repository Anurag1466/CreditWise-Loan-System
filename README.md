# Credit Risk / Loan Approval Prediction System

## Project Overview
This project is a supervised machine learning model that predicts whether a loan application will be approved based on applicant details such as income, gender, loan amount, and credit history.
The entire implementation is done using a Jupyter Notebook for step-by-step analysis and visualization.

The goal is to assist financial institutions in making data-driven loan approval decisions.

---

## Objectives
- Predict loan approval status (Approved / Not Approved)
- Perform data cleaning and preprocessing
- Handle missing values and duplicate data
- Encode categorical variables using one-hot encoding
- Train and evaluate multiple machine learning models

---

## Dataset
The dataset contains applicant information such as:
- Gender
- Income
- Loan Amount
- Credit History
- Marital Status

**Target Variable:**
- `Loan_Approved` (Yes/No)

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Workflow
1. Data Collection
2. Data Cleaning
   - Handling missing values
   - Removing duplicates
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
   - One-hot encoding
5. Train-Test Split
6. Model Training
7. Model Evaluation

![Train Test Split](https://github.com/Anurag1466/CreditWise-Loan-System/blob/452076d4811d413f2083e58e7cbd0cd08d57aed3/Screenshot%202026-04-07%20060428.png)

---


## Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes

---

## Results
- Models were evaluated using accuracy, confusion matrix, and classification report
- Naive Bayes performed best based on precision score

![Naive Bayes Results](https://github.com/Anurag1466/CreditWise-Loan-System/blob/452076d4811d413f2083e58e7cbd0cd08d57aed3/Screenshot%202026-04-07%20060428.png)

---

## Visualizations
- Bar plots
- Histograms
- Heatmaps
- Pie charts


![Heatmap](https://github.com/Anurag1466/CreditWise-Loan-System/blob/452076d4811d413f2083e58e7cbd0cd08d57aed3/Screenshot%202026-04-07%20060853.png)

---

## How to Run

1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   
2. Open Jupyter Notebook

3. Open the project file (CreditWiseLoan.ipynb)

4. Run all cells step by step
