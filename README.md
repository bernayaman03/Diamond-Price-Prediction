# Diamond Price Prediction

A machine learning project developed as part of a university group assignment at Karabük University in May 2025.

The project focuses on predicting diamond prices based on their physical and quality-related characteristics. Different regression algorithms were evaluated to identify the most suitable model.

## Features

- Data preprocessing and exploratory data analysis
- Data visualization using Matplotlib and Seaborn
- Comparison of multiple regression algorithms
- Model evaluation using cross-validation, RMSE, and R²
- Diamond price prediction using XGBoost Regressor
- A Tkinter-based desktop interface for entering diamond characteristics and displaying predicted prices

## Model Evaluation

Multiple regression models were compared using cross-validation and test data.

**XGBoost Regressor** achieved the best overall performance among the evaluated models, with the lowest RMSE and highest R² scores.

The analysis also highlighted carat weight, clarity, cut, color, and diamond dimensions as important factors influencing price predictions.

## Technologies

- Python
- Pandas and NumPy
- Scikit-learn
- XGBoost
- Matplotlib and Seaborn
- Tkinter
- Jupyter Notebook
- Joblib

## Project Files

- `DiamondPrice.ipynb` — Data analysis, preprocessing, model training, and evaluation
- `elmas_tahmin_tkinter.py` — Desktop application for diamond price prediction
- `model.pkl` — Serialized machine learning model
- `diamond_price_model.pkl` — Additional saved model
- `setup.py` — Project setup script

## Project Context

This project was developed collaboratively as a university coursework assignment. Team members contributed to the different stages of data analysis, model development, evaluation, and application integration.
