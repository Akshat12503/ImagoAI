# Mycotoxin Prediction from Hyperspectral Corn Data

## Repository Structure
```
├── imagoai-task.ipynb        # Complete end-to-end pipeline (Preprocessing, PCA, ML & MLP Models)
├── report.md                 # Short summary report
└── README.md                 # Project overview and setup instructions
```

## Objective
Predict DON concentration in corn samples using hyperspectral imaging data.

## Steps Covered
- Data Preprocessing
- Spectral Visualization
- Dimensionality Reduction (PCA)
- Model Training: RF, XGBoost, MLP
- Evaluation & Comparison

## Requirements
- Python ≥ 3.8
- scikit-learn
- xgboost
- matplotlib, seaborn

## How to Run
1. Upload dataset as `/input/TASK-ML-INTERN.csv` on Kaggle/Colab.
2. Run `imagoai-task.ipynb` sequentially.

## Metrics Used
- MAE
- RMSE
- R² Score
