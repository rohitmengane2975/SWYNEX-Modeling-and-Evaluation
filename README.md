# SWYNEX Modeling and Evaluation – Titanic Dataset

## Project Overview

This project was completed as part of the SWYNEX Technologies Data Science Internship.

The objective was to build and evaluate a baseline machine learning model to predict passenger survival using the Titanic dataset.

## Dataset

The cleaned Titanic dataset contains 891 rows and 11 columns.

The target variable is `Survived`:
- 0 = Did not survive
- 1 = Survived

## Model Used

**Logistic Regression** was used as the baseline classification model.

- Training data: 80%
- Testing data: 20%
- Test samples: 179
- Random state: 42

Categorical features were encoded, and numerical features were scaled using a preprocessing pipeline.

## Evaluation Results

- Accuracy: 80.45%
- Precision for survivors: 0.79
- Recall for survivors: 0.67
- F1-score for survivors: 0.72

### Confusion Matrix

| | Predicted Not Survived | Predicted Survived |
|---|---:|---:|
| Actual Not Survived | 98 | 12 |
| Actual Survived | 23 | 46 |

## Model Limitations

1. Only a baseline Logistic Regression model was evaluated.
2. Results may vary with a different train-test split.
3. The model missed 23 passengers who actually survived.
4. The available features may not capture every factor affecting survival.
5. Performance on this dataset does not guarantee similar results on other datasets.

## Conclusion

The baseline Logistic Regression model achieved 80.45% accuracy on the test set. Further experiments with other models and evaluation strategies may help determine whether performance can be improved.

## Files

- `SWYNEX_Modeling_and_Evaluation.ipynb` – Notebook containing model training and evaluation.
- `SWYNEX_Titanic_Cleaned.csv` – Cleaned Titanic dataset.

## Internship

Completed as part of the SWYNEX Technologies Data Science Internship.
