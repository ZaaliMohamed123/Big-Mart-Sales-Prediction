# Big Mart Sales Prediction

This project aims to predict sales for Big Mart outlets using machine learning models.

The process includes the following key steps:

1. Data Collection: The dataset is imported, containing information on various items and sales.

2. Data Analysis & Visualization:

   * Initial exploration is conducted to understand the dataset, including checking for missing values and summary statistics.
   * Visualizations such as histograms and count plots are created for both numerical and categorical columns to identify distribution patterns.
3. Data Preprocessing:

    * Checked for and handled missing values.
   * Encoded categorical features using LabelEncoder
   * Split the data into features and target.

4. Model Selection:

   * Evaluated multiple models (Lasso, RandomForestRegressor, KNeighborsRegressor, and XGBRegressor) using cross-validation and selected the best-performing model based on the mean cross-validation score.

5. Model Training :

   * Data is split into training and test sets.
   * The RandomForestRegressor model is trained on the training data.

6. Model Evaluation:
   * Evaluation is performed using R² score and Mean Absolute Error (MAE) on both training and test sets.
   * Visualizations of actual vs. predicted sales are created to compare model predictions.
