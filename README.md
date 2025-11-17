# Loan Status Prediction

This repository contains a small machine learning project that predicts loan approval status from borrower and loan features. The primary work is in a Jupyter notebook which walks through data loading, preprocessing, exploratory data analysis, model training (Decision Tree), evaluation, and interpretation.

## Quick summary
- Model: DecisionTreeClassifier (scikit-learn)
- Notebook: `model.ipynb` — full analysis and code cells
- Data: `loan_data.csv` — the dataset used for training/evaluation
- Environment: `requirements.txt` — Python dependencies

## Files in this repository

- `model.ipynb` — Jupyter notebook with the full analysis and modeling pipeline.
- `loan_data.csv` — raw dataset used by the notebook (target column: `Loan_Status`).
- `requirements.txt` — pip installable dependencies required to run the notebook.
- `README.md` — this file.

## Setup

1. Create (optional) and activate a virtual environment.

	Example (PowerShell):

	```powershell
	python -m venv .venv; .\.venv\Scripts\Activate.ps1
	```

2. Install dependencies:

	```powershell
	pip install -r requirements.txt
	```

3. Start Jupyter (if not using VS Code):

	```powershell
	jupyter notebook model.ipynb
	```

Or open `model.ipynb` directly in VS Code's Notebook editor.

## Usage

1. Ensure `loan_data.csv` is in the same folder as `model.ipynb`.
2. Open and run the notebook cells in order. The notebook includes steps for data cleaning, feature encoding, training the Decision Tree, and evaluating metrics (accuracy, confusion matrix, feature importance).

## Dataset notes

- The dataset contains common loan-application fields such as `Gender`, `Married`, `Dependents`, `Education`, `Self_Employed`, `ApplicantIncome`, `CoapplicantIncome`, `LoanAmount`, `Loan_Amount_Term`, `Credit_History`, `Property_Area`, and the target `Loan_Status`.
- If this dataset was sourced externally (e.g., Kaggle), please keep any original attributions or licensing information in the repository when redistributing.

## Results

Find model performance metrics and visualizations inside `model.ipynb`. The notebook shows accuracy, a confusion matrix, and a short discussion of model limitations (overfitting, data imbalance, etc.).

## Contributing

Small improvements are welcome: add a LICENSE, include a `data/` folder, expand tests, or provide a requirements lock file. Open an issue or submit a PR.
