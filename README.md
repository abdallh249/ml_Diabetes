# Diabetes Prediction with Machine Learning

A machine-learning project that predicts diabetes from medical attributes such as glucose, blood pressure, insulin, BMI, age, and pregnancy history.

## Workflow

1. Load and explore the diabetes dataset.
2. Replace invalid zero values with median values.
3. Split the data into training, validation, and testing sets.
4. Balance the training data using SMOTE.
5. Compare Logistic Regression, Random Forest, and XGBoost.
6. Use XGBoost to predict new patient samples.

## Technologies

- Python and Jupyter Notebook
- Pandas and NumPy
- Scikit-learn
- XGBoost and SMOTE
- Matplotlib and Seaborn

## Results

After class balancing, XGBoost achieved approximately:

- **Accuracy:** 83%
- **Diabetes recall:** 81%
- **Diabetes F1-score:** 77%

## Run the Project

```bash
git clone https://github.com/abdallh249/ml_Diabetes.git
cd ml_Diabetes
pip install pandas numpy scikit-learn xgboost imbalanced-learn matplotlib seaborn jupyter
jupyter notebook Untitled-1.ipynb
```

## Project Files

```text
├── Untitled-1.ipynb
└── diabetes.csv
```

> **Note:** This project is for educational purposes only and should not be used as a medical diagnosis tool.

## Author

[Abdallah](https://github.com/abdallh249)
