# Time Series Analysis - Forecasting Restaurant Customers

**Developed by Nowa Analytics Consulting**
*Portfolio Project by Anderson Cruz*

## Project Summary

This project demonstrates the use of **supervised machine learning** to **predict the number of customers in a restaurant** based on historical and contextual data. It was developed by **Nowa Analytics Consulting** as a portfolio project to showcase practical skills in data preprocessing, feature engineering, model building, and performance evaluation.

This type of prediction is useful for improving business planning, such as staff allocation, inventory management, and service preparation.

## Objective

The objective is to build regression models capable of accurately estimating how many customers are expected to visit the restaurant on a given day, using input features like:

* Date and time
* Day of the week
* Holidays
* Weather conditions
* Historical reservations and visits

## Project Structure

The project follows a typical data science pipeline:

1. **Data Collection & Loading**
   Import and examine datasets from `.csv` files.

2. **Data Cleaning & Preparation**

   * Handling missing values
   * Merging datasets
   * Formatting date-time features
   * Creating new variables

3. **Exploratory Data Analysis (EDA)**

   * Visualizing distributions
   * Detecting outliers
   * Correlation analysis

4. **Feature Engineering**

   * Extracting relevant components from dates
   * Encoding categorical variables
   * Normalizing/transforming features as needed

5. **Modeling & Evaluation**
   Several regression algorithms were tested and compared:

   * Linear Regression
   * Decision Tree Regressor
   * Random Forest Regressor
   * Gradient Boosting Regressor
   * XGBoost Regressor

   **Metrics used**:

   * R² Score
   * Mean Absolute Error (MAE)
   * Root Mean Squared Error (RMSE)

6. **Model Selection & Insights**
   The best model is selected based on performance, and business implications are discussed.

## Results

* The final model delivers accurate forecasts of daily customer volume.
* Feature importance analysis reveals which factors most influence customer visits.

## Technologies Used

* Python
* Pandas & NumPy
* Scikit-learn
* XGBoost
* Matplotlib & Seaborn
* Jupyter Notebook

## About This Portfolio Project

This project was created as part of my personal portfolio to demonstrate my capabilities in data science and machine learning, particularly in:

* Data preparation and EDA
* Building and tuning regression models
* Interpreting results for business use cases

