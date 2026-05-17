# Bank Note Authentication — Classification Project

## Project Overview

This repository contains a classification project to detect forged banknotes using the provided `BankNote_Authentication.csv` dataset. The analysis and model training are implemented in `code.ipynb` (Jupyter Notebook).

## Files

- `BankNote_Authentication.csv` — Dataset (features extracted from images of banknotes).
- `code.ipynb` — Notebook with data exploration, preprocessing, model training, evaluation, and example visualizations.
- `README.md` — This file.

## Dataset

The dataset contains features computed from images of genuine and forged banknotes. Typical features include variance, skewness, curtosis, and entropy. The target column indicates whether a banknote is authentic (0) or forged (1).

## Dependencies

The notebook requires Python 3.8+ and the following packages:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

Install dependencies with:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
````

## Quick Start

1. Open the project directory in your terminal or IDE.
2. Start Jupyter Notebook or Jupyter Lab:

```bash
jupyter notebook
```

3. Open `code.ipynb` and run the cells sequentially. The notebook includes sections for:
   - Data loading and inspection
   - Exploratory data analysis (visualizations)
   - Preprocessing and feature scaling
   - Model training (examples include Logistic Regression, SVM, Random Forest)
   - Evaluation (accuracy, confusion matrix, classification report)

## Reproducing Results

- Ensure `BankNote_Authentication.csv` is in the same folder as `code.ipynb`.
- Run all cells in the notebook. Models are trained using scikit-learn and results (metrics and plots) are generated inline.

## Author

Project created for a Bank Note Authentication classification task.

.
