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

- Designing the evaluation approach
- Spearman Rank Correlation analysis
- Kendall Tau analysis
- Top-K Feature Agreement
- Runtime Analysis
- ROAR (Remove and Retrain) evaluation
- Analysis and interpretation of the experimental results

The complete notebook contains the overall group project workflow. The evaluation sections listed above relate to my assigned contribution.

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

Summarises the main experimental outputs used when reviewing and comparing the XAI methods.

## Evaluation Results

The `Evaluation Results` folder contains the main visual outputs related to my evaluation work:

- `Correlation.png` – Spearman correlation heatmap
- `TopK_Agreement.png` – Top-K Feature Agreement
- `Runtime.png` – Runtime comparison
- `ROAR.png` – ROAR evaluation results

## Repository Contents

- `CompareXAI.ipynb` – complete project notebook
- `Evaluation Results/` – supporting evaluation figures
- `README.md` – repository information

## Dataset

The project uses the Breast Cancer Wisconsin Diagnostic (WDBC) dataset.

The completed notebook already contains the generated outputs and results. The original `wdbc.data` file is required only if the notebook is executed again from the beginning.
