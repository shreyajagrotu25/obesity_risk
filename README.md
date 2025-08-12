
# Obesity Risk Prediction with Explainable AI

## Overview

This project predicts the risk of obesity using machine learning and explains the predictions with **Explainable AI (XAI)** techniques.
It uses health, lifestyle, and demographic data to classify individuals into categories such as **Underweight**, **Normal Weight**, **Overweight**, **Obesity**, and **Severe Obesity**.

## Dataset

* **Source**: [Kaggle – Multi-Class Prediction of Obesity Risk](https://www.kaggle.com/competitions/playground-series-s4e2/data)
* Contains features like **Age**, **Gender**, **Height**, **Weight**, **BMI**, eating habits, physical activity, and more.

## Methods Used

* **Machine Learning**: XGBoost, Scikit-learn
* **XAI Techniques**:

  * Permutation Feature Importance (PFI)
  * SHAP values
  * Partial Dependence Plots (PDP)
  * LIME
  * Diverse Counterfactual Explanations (DiCE)

## How to Run

1. Install requirements:

   ```bash
   pip install -r requirements.txt
   ```
2. Open the notebook:

   ```bash
   jupyter notebook obesity-risk-factors-with-explainable-ai-xai-checkpoint.ipynb
   ```
3. Run the cells to train the model and view XAI results.

## Key Insights

* BMI, Age, and Physical Activity are among the top predictors.
* XAI helps explain both overall feature importance and individual predictions.
