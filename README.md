# House Price Prediction using Machine Learning 🏠📊

## Overview
This project applies machine learning techniques to predict house prices based on various property features such as total area, number of bedrooms, bathrooms, and amenities (like air conditioning and hot water heating). 

The goal of the project was to build, evaluate, and compare predictive models to determine which algorithm provides the most accurate pricing estimates, while also identifying which property features have the strongest influence on market value.

## Dataset
The dataset (`Housing.csv`) contains 545 entries with 13 columns, including both numerical features (area, bedrooms) and categorical features (mainroad, guestroom, furnishing status) which were preprocessed using one-hot encoding.

## Technologies Used
* **Python 3.x**
* **Jupyter Notebook**
* **Pandas** (Data manipulation and cleaning)
* **Scikit-learn** (Machine learning modeling and evaluation)
* **Matplotlib & Seaborn** (Data visualization)

## Project Workflow
1. **Data Exploration & Cleaning:** Checked for missing values, removed duplicates, and converted categorical text data into numeric formats using one-hot encoding.
2. **Exploratory Data Analysis (EDA):** Visualized price distributions and feature correlations using heatmaps and scatter plots.
3. **Model Training:** Split the data into 80% training and 20% testing sets. Trained two models:
   * Linear Regression
   * Random Forest Regressor
4. **Evaluation:** Compared models using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² Score.

## Key Insights & Results
* **Top Features:** Property area, number of bathrooms, and the presence of air conditioning had the highest correlation with house price.
* **Model Performance:** The basic **Linear Regression** model slightly outperformed the Random Forest Regressor on this dataset, achieving an **R² score of ~0.65** (explaining 65% of the variance in house prices).
* **Business Recommendation:** Real estate investors should prioritize properties with larger square footage and multiple bathrooms, or consider adding air conditioning as a cost-effective way to boost property value.

## Repository Structure
* `analysis.ipynb`: The complete Jupyter Notebook containing all Python code, data cleaning, modeling, and visualizations.
* `Housing.csv`: The dataset used for training and testing.
* different png containing charts.
* `summary.pdf`: A concise 1-page summary of the project findings.
