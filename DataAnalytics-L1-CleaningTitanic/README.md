# Titanic Data Cleaning — Data Analytics Level 1, Task 3

## Objective
Clean a messy dataset (Titanic passenger data) — handle missing values, 
check duplicates, and produce an analysis-ready dataset.

## What I did
- Loaded the Titanic dataset (891 rows, 12 columns)
- Found missing values in Age (177), Cabin (687), Embarked (2)
- Filled Age with median value
- Dropped Cabin column (77% missing — too much to reliably fill)
- Filled Embarked with mode (most common value)
- Checked for duplicate rows (none found)
- Saved cleaned dataset as titanic_cleaned.csv

## Tools used
Python, pandas, Google Colab

## Files
- OIBSIP.ipynb — the notebook with all code and explanations
- titanic_cleaned.csv — the final cleaned dataset