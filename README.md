# IBM HR Analytics Attrition Dataset

## Overview

This repository contains the IBM HR Analytics Attrition dataset in compressed form. The data can be used for employee attrition analysis, predictive modeling, and HR analytics exploration.

## Contents

- `ibm-hr-analytics-attrition-dataset.zip`
  - `WA_Fn-UseC_-HR-Employee-Attrition.csv`

## Usage

1. Extract the archive.
2. Load the CSV file into your analysis tool or environment.
   - Example using Python and pandas:
     ```python
     import pandas as pd

     df = pd.read_csv("WA_Fn-UseC_-HR-Employee-Attrition.csv")
     print(df.head())
     ```
3. Perform data cleaning, feature engineering, and modeling as needed.

## Notes

- The dataset includes employee information and attrition labels.
- Use the data for learning, experimentation, and demonstration of HR analytics techniques.

## Recommended Tools

- Python
- pandas
- Jupyter Notebook or VS Code
- scikit-learn
- matplotlib / seaborn