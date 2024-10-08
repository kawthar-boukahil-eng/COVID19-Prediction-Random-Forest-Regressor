# COVID19-Prediction-Random-Forest-Regressor
## Project Overview
This project aims to predict the spread of COVID-19 using various regression techniques, including Linear Regression and Random Forest Regressor. It explores the relationship between different variables such as confirmed cases and fatalities across multiple countries. The predictions help governments and healthcare organizations plan resources more effectively, optimize healthcare systems, and make data-driven decisions for containment strategies.

## Problem Statement
During the COVID-19 pandemic, predicting the spread of the virus is crucial for proactive decision-making. Accurate predictions of confirmed cases and fatalities can help in:

- Planning hospital resources, medical supplies, and vaccine distribution.
- Avoiding the overloading of healthcare systems.
- Informing government policies on lockdowns and re-openings based on real-time data.

## Objectives
1. **Prediction of the Most Affected Countries:** Identifying the countries most impacted by COVID-19.
2. **Prediction of Confirmed Cases:** Forecasting the number of confirmed cases to understand the evolution of the disease.
3. **Prediction of Fatalities:** Estimating the number of fatalities to assess the impact of the disease on the population and plan medical resources accordingly.

## Data Analysis and Exploration
An Exploratory Data Analysis (EDA) was conducted to understand the dataset properties, identify correlations between variables, and prepare data for modeling. Below are some key points:

- **Target Variables:** ConfirmedCases, Fatalities.
- **Data Dimensions:** 35,995 rows and 6 columns.
- **Data Types:**
  - Object (3 columns)
  - Float64 (2 columns)
  - Int64 (1 column)
- **Missing Values:** No missing values in `Id`, `Country_Region`, `Date`, `ConfirmedCases`, and `Fatalities`. However, 57% of the `Province_State` values are missing and were dropped during preprocessing.

## Libraries Used
- **Pandas and Numpy:** For data manipulation and handling.
- **Seaborn and Matplotlib:** For creating static visualizations.
- **Plotly:** For interactive visualizations.
- **Scikit-learn (Sklearn):** For training and evaluating models.

## Data Preprocessing and Visualization
- **Data Cleaning:** Dropped columns with a high percentage of missing values (`Province_State`).
- **Heatmaps:** Visualized missing values and correlations between variables.
- **Pie Charts:** Illustrated the distribution of confirmed cases and fatalities by country.
- **Pairplot:** Showed relationships between confirmed cases and fatalities.
- **Scatter Plot:** Displayed the distribution of cases and highlighted trends or correlations.

## Modeling Approach
The project uses a combination of regression techniques to predict the spread of COVID-19. The following models were applied:

- **Linear Regression:** To establish a baseline prediction model.
- **Random Forest Regressor:** For more accurate predictions and handling non-linear relationships in the data.

## Model Evaluation Metrics
- **Mean Absolute Error (MAE):** Measures the average magnitude of the errors in a set of predictions.
- **Mean Squared Error (MSE):** Measures the average squared difference between the predicted and actual values.
- **Explained Variance Score:** Quantifies how much of the variance in the target variable is explained by the model.

## Project Files
- **COVID19_Prediction.ipynb:** The Jupyter Notebook containing the complete analysis, data visualization, and modeling.
- **Dataset:** Contains the training data used for predictions.
- **README.md:** This documentation file.

## Usage Instructions
- Load the dataset and explore the initial properties.
- Visualize the data using the provided plots and charts.
- Train and evaluate the models using the provided code.
- Modify parameters or add new models to improve predictions.
 ## Contributors
Kawthar BOUKAHIL
Abderraouf SAHEB
