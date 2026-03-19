# Customer Churn Analysis

This project analyzes customer churn for a telecom company using Python. It includes data cleaning, preprocessing, visualization, and machine learning to predict customer churn.

## Repository Structure

```

customer-churn-analysis/
│
├─ churn_analysis.ipynb           # Jupyter notebook with complete analysis
├─ WA_Fn-UseC_-Telco-Customer-Churn.csv  # Dataset
├─ requirements.txt               # Python dependencies

````

## Features

- Data preprocessing:
  - Handle missing values
  - Encode categorical columns
  - Scale numerical features
- Exploratory Data Analysis (EDA):
  - Churn distribution
  - Churn vs contract type
  - Monthly charges distribution by churn
  - Correlation heatmaps
  - Churn rate by internet service and payment method
- Machine Learning Models:
  - Logistic Regression
  - Decision Tree (unconstrained and pruned)
  - Random Forest
  - XGBoost
- Model Evaluation:
  - Accuracy, Precision, Recall, F1-Score
  - Confusion matrices
  - ROC curves and AUC

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Maheen-Fatima-1/customer-churn-analysis.git
cd customer-churn-analysis
````

2. Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

1. Open `churn_analysis.ipynb` in Jupyter Notebook.
2. Run each cell sequentially to:

   * Load and preprocess the dataset
   * Visualize patterns and correlations
   * Train and evaluate ML models
   * Compare models and visualize ROC curves

## Requirements

* Python >= 3.8
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* xgboost

## Insights

* Long-tenure customers and those with 1- or 2-year contracts are less likely to churn.
* Fiber optic users, electronic check payers, and streaming service subscribers are at higher risk of churn.
* Logistic Regression achieved the highest recall, making it best for identifying customers likely to churn.

## Notes

* Each model was tuned with thresholds to maximize F1-score or recall.
* Dataset preprocessing includes handling missing `TotalCharges` values and encoding categorical variables.
* Target variable `Churn` is encoded as 1 for churned customers, 0 otherwise.

## GitHub Repository

[https://github.com/Maheen-Fatima-1/customer-churn-analysis](https://github.com/Maheen-Fatima-1/customer-churn-analysis)

## Author

Maheen Fatima
Data Science Enthusiast

```
