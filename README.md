# CompareXAI: Feature Attribution Comparison Framework

## Overview

CompareXAI is a Python-based Explainable AI (XAI) framework that
compares SHAP, LIME, and Permutation Feature Importance using the Breast
Cancer Wisconsin Diagnostic (WDBC) dataset.

## Requirements

-   Python 3.10+
-   Dataset file: `wdbc.data`

Install dependencies:

``` bash
pip install numpy pandas matplotlib scikit-learn shap lime scipy
```

## Project Files

    CompareXAI.py
    wdbc.data
    README.md

## Running the Project

1.  Place `CompareXAI.py` and `wdbc.data` in the same folder.
2.  Install the required libraries.
3.  Run:

``` bash
python CompareXAI.ipynb
```

## Workflow

-   Load WDBC dataset
-   Preprocess data
-   Train ML models
-   Evaluate performance
-   Generate SHAP explanations
-   Generate Global LIME explanations
-   Generate Permutation Importance
-   Compare XAI methods
-   Perform correlation analysis
-   Compute Top-K agreement
-   Perform runtime comparison
-   Perform ROAR evaluation
-   Save plots and CSV results

## Models

-   Logistic Regression
-   Decision Tree
-   Random Forest
-   Support Vector Machine (SVM)

## XAI Methods

-   SHAP
-   Global LIME
-   Permutation Feature Importance

## Outputs


### Figures

-   SHAP_Summary.png
-   Correlation.png
-   Runtime.png
-   ROAR.png
-   TopK_Agreement.png

## Notes

-   Ensure `wdbc.data` is available before execution.
-   Output files are saved automatically in the project directory.

## Author

Project: **CompareXAI: Feature Attribution Comparison Framework**
