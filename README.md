Project Overview

This project applies Regression Analysis to predict house prices using features like Size, Location, and Number of Rooms.
We use the Housing.csv dataset (from Kaggle) and build a Linear Regression model in Python with Scikit-learn.

Objectives

Load and explore the dataset.

Preprocess data (handle missing values, scale numerical data, encode categorical features).
Perform feature selection and correlation analysis.
Train a Linear Regression model.
Evaluate performance using RMSE and R².
Identify important predictors of house prices.

Dataset Details

Dataset Name: Housing.csv

Key Columns:

area → Size (sq. ft)
bedrooms → Number of Rooms
bathrooms → (extra predictor)
stories, parking → Additional predictors
price → Target variable
furnishingstatus, mainroad, airconditioning, prefarea → Categorical features

Technologies Used

Python 3
Google Colab / Jupyter Notebook

Libraries:

pandas, numpy → Data handling
matplotlib, seaborn → Visualization
scikit-learn → ML model & evaluation

Steps Implemented
Step 1: Load & Explore Data

Checked dataset shape & head
Handled missing values
Visualized distributions of numerical variables (Size, Price)
Detected potential outliers

Step 2: Data Preprocessing

Normalized numerical features using StandardScaler
Encoded categorical features with OneHotEncoder
Combined preprocessing using ColumnTransformer

Step 3: Feature Selection

Correlation analysis (heatmap)
Removed low-impact predictors if necessary

Step 4: Model Training

Train-test split (80-20, random state fixed for reproducibility)
Linear Regression model trained with scikit-learn

Step 5: Model Evaluation

RMSE (Root Mean Squared Error)
R² (Coefficient of Determination)

Step 6: Feature Insights

Identified most important predictors using Permutation Importance
Visualized feature importance with bar plot

Results

RMSE: (example) ~ 1.25e06
R²: (example) ~ 0.78

Key Insights:

Larger area (size) strongly increases price.
Number of rooms positively affects price.
Location features (like main road, preferred area) also influence pricing.

Expected Insights

Correlation between Size, Rooms and Price.
The effect of Location & Amenities on house prices.
The model’s ability to generalize and predict real-world prices.

Deliverables

Trained Linear Regression model
Predictions on test data (actual vs predicted)
Evaluation metrics (RMSE & R²)
Feature importance insights


BY AUTHOR - Likhitha Gopal
