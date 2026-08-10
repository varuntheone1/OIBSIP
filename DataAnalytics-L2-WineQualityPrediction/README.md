# Wine Quality Prediction

Oasis Infobyte Data Analytics Internship — Level 2, Task 2.

## Objective

Predict red-wine quality from physicochemical properties and compare Random Forest, SGD, and Support Vector classifiers.

## Dataset

`winequality-red.csv` is the user-provided UCI Wine Quality red-wine dataset: 1,599 samples with 11 physicochemical features and one quality score.

## Project checklist covered

- Original quality distribution and class-imbalance discussion
- Feature distributions and correlation heatmap
- Three-class feature engineering: Low (3–4), Medium (5–6), High (7–8)
- Stratified 80/20 train/test split
- Random Forest, SGD, and SVC models
- Accuracy, classification reports, confusion matrices, and comparison table
- Random Forest feature-importance chart
- Conclusion and deployment recommendations

## Run

```bash
pip install -r requirements.txt
jupyter notebook Wine_Quality_Prediction.ipynb
```

Run every cell from top to bottom. Charts are saved to `outputs/`.
