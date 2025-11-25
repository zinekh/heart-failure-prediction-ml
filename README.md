# Heart Failure Prediction ML

This project implements a Machine Learning pipeline to predict the presence of heart disease in patients based on medical attributes.

## Goal
Binary Classification of Heart Disease (0: Normal, 1: Heart Disease) using the [Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction).

## Results
We achieved **~90% Accuracy** on the test set with both models:
- **Logistic Regression**: 90% Accuracy (Preferred for interpretability)
- **Random Forest**: 90% Accuracy

## How to Run

1.  **Setup Environment**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```

2.  **Run Notebook**
    Open `heart_failure_prediction.ipynb` in Jupyter or VS Code and run all cells.