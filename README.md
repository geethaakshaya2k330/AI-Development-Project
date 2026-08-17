# CompareXAI: Feature Attribution Comparison Framework

## Project Overview

CompareXAI is a group Explainable AI (XAI) project based on the Breast Cancer Wisconsin Diagnostic (WDBC) dataset.

The project compares three feature-attribution methods:

- SHAP
- Global LIME
- Permutation Feature Importance

The complete project workflow is available in `CompareXAI.ipynb`.

## My Contribution

My main responsibility in the group project was the evaluation and performance analysis of the XAI methods.

My contribution included:

- Designing the evaluation framework
- Spearman Rank Correlation analysis
- Kendall Tau analysis
- Top-K Feature Agreement
- Runtime Analysis
- ROAR (Remove and Retrain) evaluation
- Analysis and interpretation of the experimental results

The complete notebook contains the overall group project workflow. The evaluation tasks listed above relate to my assigned contribution.

## Relevant Notebook Sections

The main technical evidence for my contribution is available in `CompareXAI.ipynb`.

### Correlation Analysis

Contains the Spearman Correlation and Kendall Tau calculations used to compare the similarity between feature rankings produced by the XAI methods.

### Top-K Feature Agreement

Compares the overlap between the highest-ranked features identified by SHAP, Global LIME and Permutation Feature Importance.

### Runtime Comparison

Compares the execution time of the XAI methods during the project experiment.

### ROAR Evaluation

Uses a Remove and Retrain approach to examine model performance after removing features identified as important.

### Final Comparison Summary

Provides a summary of the experimental outputs used when reviewing the final results.

## Evaluation Results

The `Evaluation Results` folder contains supporting outputs related to my evaluation tasks:

- `Correlation.jpeg` – Spearman correlation heatmap
- `TopK_Agreement.jpeg` – Top-K Feature Agreement results
- `Runtime.jpeg` – Runtime comparison results
- `ROAR.jpeg` – ROAR evaluation results

These figures provide visual evidence of the evaluation results discussed in my individual contribution.

## Repository Contents

- `CompareXAI.ipynb` – complete group project notebook with code and saved outputs
- `Evaluation Results/` – supporting outputs for the evaluation tasks
- `README.md` – project and repository information

## Requirements

The notebook can be opened using Google Colab or Jupyter Notebook.

The main Python libraries used are:

```bash
pip install numpy pandas matplotlib scikit-learn shap lime scipy
