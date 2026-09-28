# Un-analisi-del-rischio-di-default-delle-imprese-italiane
This repository contains the Python code used for the empirical analysis
developed in the Master's thesis:

"Un analisi del rischio di default delle imprese italiane"

## Repository structure

### 01_data_preparation.ipynb
Contains the procedures used to construct the final dataset:
- sample selection
- definition of default events
- t-3 matching
- missing value treatment
- winsorization
- logarithmic transformations
- categorical encoding
- final dataset construction

### 02_empirical_analysis.ipynb
Contains the empirical analysis:
- Logistic Regression
- Lasso and Ridge Logistic Regression
- XGBoost
- ROC and AUROC
- Youden Index
- confusion matrices
- performance metrics
- SHAP values
- SHAP interaction values

## Data availability

The dataset used in the analysis was obtained from AIDA – Bureau van Dijk.
Due to licensing restrictions, the underlying data are not included in this repository.
