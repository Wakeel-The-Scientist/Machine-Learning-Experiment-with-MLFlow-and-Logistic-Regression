# Machine Learning Experiment with MLFlow and Logistic Regression

## Overview
This project demonstrates a machine learning workflow using **Logistic Regression** on the **Iris dataset**, while leveraging **MLFlow** for experiment tracking. The main objectives are:
- Training a Logistic Regression model
- Evaluating model performance
- Logging metrics and artifacts with MLFlow

## Dataset
- **Dataset:** Iris dataset (from `sklearn.datasets`)
- **Features:** 4 numerical features
- **Target Classes:** 3 (Setosa, Versicolor, Virginica)

## Model Training
- **Algorithm:** Logistic Regression
- **Hyperparameters:**
  - `penalty`: l2
  - `solver`: lbfgs
  - `max_iter`: 1000
  - `multi_class`: auto
  - `random_state`: 8888
- **Data Split:** 80% training, 20% testing

## Evaluation
- **Metric:** Accuracy
- **Result:** Computed using `accuracy_score` from `sklearn.metrics`

## MLFlow Integration
- **Tracking URI:** `http://127.0.0.1:5000`
- **Logged Parameters:** Hyperparameters used for training
- **Logged Metric:** Model accuracy
- **Artifact:** Trained Logistic Regression model

## Conclusion
This experiment successfully demonstrates the use of **MLFlow** to track and log a machine learning model. Future improvements could include hyperparameter tuning, cross-validation, and experimenting with other models.

## Next Steps
- Extend the experiment with other classifiers (e.g., SVM, Random Forest)
- Automate MLFlow logging in a pipeline
- Deploy the model using MLFlow serving

