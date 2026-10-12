# DDA555-project-2
This project improves a classification model by combining feature selection with
hyperparameter tuning for a Gaussian Naive Bayes (`GaussianNB`) classifier.
The project is implemented in a Jupyter notebook. Open the notebook and run the cells sequentially to reproduce the analysis and results.

## Requirements

Install the required Python packages with:

```bash
pip install numpy pandas scikit-learn seaborn matplotlib
```

## Structure
1. Analyze a dataset (6 points)
   1.1 MI Exploratory Data Analysis (EDA)
   1.2 Univariate Analysis
   1.3 Numeric features vs. outcome
2. Train a binary classifier (5 points)
  2.1 Mu Split Dataset into Training and Testing Set
  2.2 Train a baseline model.
3. Improve the model's performance (4 points)

## Reproducibility

The cross-validation split is reproducible because `random_state=1001` is set.
For fully reproducible results, also keep the data-preparation steps, selected
feature list, package versions, and random seeds unchanged.
