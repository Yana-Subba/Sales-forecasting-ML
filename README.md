# Sales Forecasting Using Machine Learning

A Machine Learning project that predicts future sales using historical retail sales data. This project compares multiple regression models to identify the most accurate algorithm for sales prediction.

# Project Overview

Sales forecasting is an important task for businesses to estimate future sales, optimize inventory, improve financial planning, and make better business decisions.
In this project, historical retail sales data is analyzed, preprocessed, and used to train multiple Machine Learning models. The performance of each model is evaluated using different metrics to determine the best-performing algorithm.

# Objectives

- Predict future sales using historical retail sales data.
- Compare multiple Machine Learning algorithms.
- Evaluate model performance using regression metrics.
- Visualize actual vs predicted sales.
- Save the trained model for future predictions.
  
# Dataset

The dataset contains historical retail sales information with features such as:

- Product Type
- Net Quantity
- Gross Sales
- Discounts
- Returns
- Total Net Sales (Target Variable)
  
# Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib

# Machine Learning Models

The following regression algorithms were implemented:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

# Model Evaluation Metrics

The models are evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Example Results:

| Model | MAE | RMSE | R² Score |
|--------|------|------|---------|
| Linear Regression | 0.00 | 0.00 | 1.000 |
| Decision Tree | 3.84 | 16.35 | 0.9936 |
| Random Forest | 3.90 | 16.64 | 0.9934 |

Best Performing Model: Linear Regression (based on this dataset)

# Visualizations

The project includes:

- Actual vs Predicted Sales Graph
- Feature Importance Plot
- Model Performance Comparison
- Prediction Results Table

# Installation

Clone the repository:
bash
git clone https://github.com/your-username/Sales-Forecasting-ML.git

Move into the project directory:
bash
cd Sales-Forecasting-ML

Install dependencies:
bash
pip install -r requirements.txt

# Run the Project

Open the notebook:
notebook/Sales Forecasting ML.ipynb

Run all cells to:

- Load the dataset
- Preprocess the data
- Train Machine Learning models
- Compare model performance
- Save the trained model
- Generate prediction outputs

# Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Selection
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Compare Algorithms
10. Predict Future Sales
11. Save Model
12. Visualize Results

# Future Improvements

- Deploy the model using Flask or Streamlit
- Add time-series forecasting models (ARIMA, Prophet, LSTM)
- Hyperparameter tuning
- Interactive dashboard
- Real-time sales prediction

# Learning Outcomes
This project demonstrates:

- Data preprocessing
- Regression modeling
- Model comparison
- Performance evaluation
- Data visualization
- Model serialization using Joblib

# Author
Yana Subba
B.Tech in Computer Science & Engineering
Machine Learning & Data Science Enthusiast
