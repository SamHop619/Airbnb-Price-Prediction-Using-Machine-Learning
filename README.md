# Airbnb-Price-Prediction-Using-Machine-Learning
Built and evaluated machine learning models to predict Airbnb listing prices in New York City using open Kaggle data. Compared Ridge Regression, Random Forest, and XGBoost models with hyperparameter tuning (GridSearchCV) to identify key price drivers and deliver actionable pricing insights for hosts.

# Airbnb Price Prediction

## Overview
This project uses machine learning to predict Airbnb listing prices in New York City based on the Kaggle "NYC Airbnb Open Data" dataset. The goal is to provide insights that help hosts set competitive and fair prices using data-driven methods.

## Dataset
Source: [Kaggle - NYC Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)  
The dataset includes features like room type, neighborhood group, availability, and minimum nights.

## Models Used
- Ridge Regression (Linear)
- Random Forest (Ensemble)
- XGBoost (Boosted Trees)

## Methods
- **Feature Selection:** Identified top predictors such as room type, neighborhood group, and availability.
- **Hyperparameter Tuning:** Applied `GridSearchCV` to optimize model parameters.
- **Model Evaluation:** Compared performance using RMSE.

## Results
- **Best Model:** XGBoost achieved the lowest RMSE and provided strong interpretability.
- **Key Insights:**  
  - Room type and location are major determinants of price.  
  - Availability affects both demand and listing cost.  

## Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Jupyter Notebook

## Files
- `Mini_Project_3_Airbnb_Price_Prediction.ipynb` – Main notebook for data cleaning, modeling, and visualization.  
- `Mini_Project_3_Presentation.pdf` – Summary presentation of findings and business recommendations.

## Author
Sam Hopkins  
Business Management Graduate | Aspiring Data Analyst  
