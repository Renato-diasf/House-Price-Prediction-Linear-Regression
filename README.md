# House Price Prediction using Linear Regression

Welcome to the **House Price Prediction** repository! This project focuses on building a **Linear Regression model** to predict house prices based on various features such as area, number of garages, bathrooms, fireplaces, marble finishing, and floors. The dataset used in this project was sourced from [Kaggle](https://www.kaggle.com/greenwing1985/housepricing) and modified for educational purposes.

---

## Project Overview

The goal of this project is to:
1. Explore and analyze a dataset containing house features and prices.
2. Build a **Linear Regression model** to predict house prices.
3. Evaluate the model's performance using metrics like **R²**, **Mean Squared Error (MSE)**, and **Root Mean Squared Error (RMSE)**.
4. Create a simple simulator to predict house prices based on user input.

---

## Dataset

The dataset contains the following features:
- **prices**: House prices (target variable).
- **area**: Area of the house.
- **garage**: Number of garage spaces.
- **bathrooms**: Number of bathrooms.
- **fireplaces**: Number of fireplaces.
- **marble**: Whether the house has white marble finishing (1) or not (0).
- **floors**: Whether the house has more than one floor (1) or not (0).

---

## Tools & Technologies

- **Python**: Primary programming language.
- **Pandas**: Data manipulation and analysis.
- **Seaborn & Matplotlib**: Data visualization.
- **Scikit-learn**: Machine learning model implementation.
- **Jupyter Notebook**: Interactive environment for code execution.

---

## Key Steps

1. **Data Loading & Exploration**:
   - Load the dataset using Pandas.
   - Perform exploratory data analysis (EDA) to understand the data distribution and relationships.

2. **Data Visualization**:
   - Create visualizations (box plots, histograms, pair plots) to analyze the relationships between variables.

3. **Model Building**:
   - Split the data into training and testing sets.
   - Train a Linear Regression model using Scikit-learn.

4. **Model Evaluation**:
   - Evaluate the model using metrics like R², MSE, and RMSE.
   - Generate predictions for the test dataset.

5. **Price Prediction Simulator**:
   - Create a simple simulator to predict house prices based on user input.

---

## Results

- **R² Score**: The model achieved an R² score of **0.67** on the test dataset, indicating a reasonable fit.
- **Key Insights**: Features like **floors** and **marble finishing** showed the strongest positive correlation with house prices.

---
