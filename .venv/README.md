# AI-Oriented Flight Data Analysis (Python)

This project demonstrates an end-to-end, beginner-friendly data workflow for an AI-oriented scenario:
synthetic flight telemetry data generation, exploratory data analysis (EDA), preprocessing, visualization,
and a basic machine learning model for event prediction.

## What I did
- Generated a synthetic flight telemetry dataset (to simulate real-world sensor signals)
- Performed EDA and visualizations
- Introduced missing values and applied simple imputation
- Trained a baseline ML classifier (Logistic Regression)
- Evaluated the model using ROC-AUC and classification metrics
- Interpreted feature coefficients to understand signal impact (wind, yaw rate, battery, GPS quality)

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib
- scikit-learn

## How to run
```bash
pip install -r requirements.txt
jupyter notebook
