# Breast Cancer Classification — Hyperparameter Optimization

Comparison of HPO techniques on the Wisconsin Breast Cancer Dataset using Random Forest Classifier.

## Techniques Used
- Manual HPO (n_estimators, min_samples_leaf)
- RandomizedSearchCV
- GridSearchCV

## Results
| Method | Accuracy |
|--------|----------|
| Base RF (default) | ~93.86% |
| Manual HPO | ~94.74% |
| RandomizedSearchCV | ~94% |
| GridSearchCV | ~94% |

## Tech Stack
Python, Scikit-learn, Pandas, Seaborn, Matplotlib

## Dataset
Wisconsin Breast Cancer Dataset — 569 samples, 30 features  
Target: Malignant (1) vs Benign (0)
