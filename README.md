# medical-cost-prediction
Predicting Insurance Charges based on patient attributes using ML models

# Medical Cost Prediction 

This project predicts individual medical insurance charges using regression models based on personal attributes such as age, BMI, smoking status, and more.

## Project Overview

- Dataset: [Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- Goal: Predict medical insurance charges using features like age, sex, BMI, number of children, smoker status, and region.

## Key Insights

- **Smokers** incur significantly higher charges.
- **Age** and **BMI** have a strong positive correlation with charges.
- **Sex** and **Region** have minimal effect on cost predictions.

## Models Used

- Linear Regression
- Random Forest Regressor 
- XGBoost Regressor

> Final Model: **Random Forest Regressor** achieved the best performance with R² = 0.90 on the test set.

## Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## Files Included

- `Medical_Cost_Prediction.ipynb` – Full analysis and modeling notebook

---

*This project is part of my machine learning portfolio. I’m currently building more real-world ML projects — stay tuned!*
