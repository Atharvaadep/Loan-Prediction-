# Loan Prediction Project

This project focuses on predicting loan approval status based on various applicant and loan features using machine learning techniques.

---

## Project Overview

The goal is to build and compare multiple classification models to predict whether a loan application will be approved (`Loan_Status`).

---

## Dataset

- The dataset contains information about loan applicants and their loan details.
- It includes features like `Gender`, `Married`, `Dependents`, `Education`, `Self_Employed`, `ApplicantIncome`, `CoapplicantIncome`, `LoanAmount`, `Loan_Amount_Term`, `Credit_History`, and `Property_Area`.
- The target variable is `Loan_Status` (Y: approved, N: not approved).

---

## Project Steps

1. **Data Loading and Exploration**
   - Understanding data dimensions, feature types, missing values, and distributions.
   - Visualizing categorical and numerical features using pie charts, bar plots, histograms, and heatmaps.

2. **Data Cleaning and Preprocessing**
   - Handling missing values via mode or mean imputation.
   - Encoding categorical variables using one-hot encoding.
   - Removing outliers using the IQR method.
   - Normalizing skewed features with square root transformation.
   - Scaling features with MinMaxScaler.

3. **Exploratory Data Analysis (EDA)**
   - Distribution analysis of features.
   - Relationship analysis between features and target variable.
   - Correlation heatmap visualization.

4. **Model Building and Evaluation**
   - Trained multiple classifiers including Decision Tree, Random Forest, Naive Bayes, Ridge Classifier, and K-Nearest Neighbors.
   - Performed hyperparameter tuning via loops (can be improved with GridSearchCV).
   - Evaluated models based on training and testing accuracy.
   - Visualized KNN accuracy across different `k` values.

---

## Technologies Used

- Python 3.x
- Pandas, NumPy for data manipulation
- Matplotlib, Seaborn for visualization
- Scikit-learn for machine learning models and preprocessing
- Termcolor for colored console output

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/loan-prediction.git
