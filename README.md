# Loan Status Prediction Using DecisionTreeClassifier

This project uses a Decision Tree Classifier to predict loan status based on provided borrower and loan features. The workflow involves data preprocessing, exploratory analysis, model training, evaluation, and results interpretation.


## Project Overview

The goal of this notebook is to develop a machine learning model that can accurately classify loan applications as approved or not approved, based on features such as applicant income, education, property area, loan amount, and credit history. The classifier used is `DecisionTreeClassifier` from `scikit-learn`.

## Dataset

- **Source:** [Kaggle Loan Status Prediction](https://www.kaggle.com/datasets)
- The dataset contains features like `Gender`, `Married`, `Dependents`, `Education`, `Self_Employed`, `AppicantIncome`, `CoapplicantIncome`, `LoanAmount`, `Loan_Amount_Term`, `Credit_History`, and `Property_Area`.
- The target variable is `Loan_Status` (Y/N).

## Installation & Requirements

Before running the notebook, ensure you have the following dependencies installed:


## Usage

To reproduce the results:

1. Clone the repository or download the notebook.
2. Place the data file (e.g., `loan-data.csv`) in the working directory.
3. Run the notebook:


4. Follow the notebook for preprocessing, training, and evaluation steps.

## Project Structure

├── loan-status-prediction-decisiontreeclassifier.ipynb
├── README.md
└── loan-data.csv


## Results

- Decision tree classifier is trained and evaluated on the processed dataset.
- Performance metrics such as accuracy, confusion matrix, and visualization of results are presented.
- Insights regarding important features and model limitations are discussed in the notebook.

## Contributing

Feel free to fork the project, open issues, or submit pull requests if you have suggestions, improvements, or bug fixes.
