# Seizure Prediction — ML Assignment

## Overview
Investigation of how preprocessing choices, model complexity,
and regularization affect generalisation in epileptic seizure prediction.

## Datasets
- UCI Epileptic Seizure Recognition (11,500 samples)
- Bonn University EEG (500 samples)
- Kaggle-style EEG (2,000 samples, severe imbalance)

## Contents
| File | Description |
|------|-------------|
| `seizure_prediction.ipynb` | Full Colab notebook (Steps 1–7) |
| `IEEE_Report.docx` | IEEE format report |
| `Presentation.pptx` | 10-slide presentation |
| `*.png` | Result graphs |

## Steps Covered
1. Dataset Collection
2. Preprocessing Pipelines (A and B)
3. Baseline Logistic Regression
4. Overfitting & Underfitting
5. Regularization Study (L1, L2, Elastic Net)
6. Class Imbalance Handling (SMOTE, Undersampling, Class Weighting)
7. Comparative Analysis

## Results
- Best pipeline: Pipeline A (normalize → feature select)
- Best regularizer: Elastic Net (mean F1 = 0.852)
- Best imbalance technique: Class Weighting