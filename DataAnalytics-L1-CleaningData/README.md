# Data Cleaning and Preprocessing: Titanic Dataset

Oasis Infobyte Data Analytics Internship — Level 1, Task 3.

## Objective

Demonstrate a transparent, professional data-cleaning workflow that converts the Titanic passenger dataset into an analysis-ready file.

## Dataset

`titanic_raw.csv` is the user-provided Titanic passenger dataset (891 records, 12 columns). The original file is preserved unchanged.

## Cleaning performed

- Data-quality report: null counts, duplicate rows, types, and value-range review.
- Standardised column names and categorical text values.
- Imputed missing age using the median within each passenger class.
- Imputed the two missing embarkation values with the mode.
- Removed `Cabin` because 77% of values are missing and cannot be responsibly inferred.
- Checked exact duplicates; none were found or removed.
- Used IQR to review numeric outliers and retained plausible historical fares.
- Corrected types for IDs, tickets, categories, and numerical measures.
- Produced a before-versus-after quality summary and saved `titanic_cleaned.csv`.

## Files

```text
DataAnalytics-L1-CleaningData/
├── Data_Cleaning.ipynb
├── titanic_raw.csv
├── titanic_cleaned.csv
├── README.md
└── requirements.txt
```

## Tools

Python, Pandas, NumPy, Matplotlib, and Jupyter Notebook.

## Run

```bash
pip install -r requirements.txt
jupyter notebook Data_Cleaning.ipynb
```

Run all cells from top to bottom; the cleaned CSV and numeric outlier-review chart are written automatically.
