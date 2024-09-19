# LoanStatusPrediction

![Loan Status Prediction](https://github.com/user-attachments/assets/4b9d683b-4dc4-44e1-8d13-4f6d9e230fc4)

## Project Overview

This project aims to assist companies in automating the loan approval process. Companies need to verify several parameters to approve a loan for a person. The system developed here will streamline this workflow, predicting loan approval based on various factors using machine learning algorithms.

## Workflow

The process follows a structured workflow, automating the loan approval steps as shown below:

![Workflow Diagram](https://github.com/user-attachments/assets/3cf36c59-2ff8-46b1-98a9-54385b8b3d85)

1. Input borrower data (e.g., income, credit history, etc.).
2. Pre-process the data (cleaning and feature selection).
3. Predict loan approval status using a machine learning model.

## Machine Learning Model

We used **Support Vector Machine (SVM)** as our primary algorithm to predict whether a loan will be approved or rejected. The `Loan_Status` column in the dataset has been encoded with the following values:
- **1**: Loan Approved
- **0**: Loan Rejected

## Dependencies

The project requires the following Python packages:
- pandas
- numpy
- scikit-learn

Install them using:

```bash
pip install -r requirements.txt
```

