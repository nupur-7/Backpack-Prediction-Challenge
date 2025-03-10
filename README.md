# Backpack-Prediction-Challenge
Kaggle Playground Series - Season 5, Episode 2 February 2025 [Backpack Prediction Challenge]

This project aims to predict the price of backpacks based on various features such as brand,
material, size, compartments, waterproofing, style, color, and weight capacity. The goal is to
develop a machine learning model that accurately estimates backpack prices given these attributes.

## Data Preprocessing
Missing values were handled using mode imputation and forward/backward filling. Categorical
variables were encoded using label encoding or one-hot encoding, and numerical features were
normalized if necessary.

## Model Selection & Training
Several regression models were trained, including Naïve Bayes, Decision Tree, Random Forest, and
KNN. The models were evaluated using MAE, MSE, and R² score to determine their effectiveness.

## Model Optimization
Hyperparameters were tuned using Grid Search and Random Search to enhance model performance.
Feature selection techniques were applied to improve predictions.

The best-performing model, Random Forest, was used to generate price predictions for the test
dataset. The final predictions were saved in submission.csv, including the id and predicted Price
rounded to three decimal places.
