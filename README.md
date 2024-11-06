# E-commerce Customer - Linear Regression Project
**By: Syamsul Rizal Fany**

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/syamsul-rizal-fany-410bb6325/)

## Overview
This project focuses on predicting the "Yearly Amount Spent" by e-commerce customers based on their session data, time spent on mobile apps and websites, and membership duration. The goal is to help the company decide where to focus its development efforts: on the mobile app experience or the website.

## Project Objective
To analyze the relationship between various customer behavior metrics and the yearly amount spent to provide data-driven recommendations on where the company should focus its development efforts.

## Dataset
The dataset used for this project contains customer details such as:

- **Avg. Session Length**: Average time spent on in-store style advice sessions.
- **Time on App**: Average time spent on the mobile app.
- **Time on Website**: Average time spent on the website.
- **Length of Membership**: Duration of customer membership in years.
- **Yearly Amount Spent**: Total money spent by the customer in a year.

## Approach
The project involved the following steps:

1. **Exploratory Data Analysis (EDA)**: Visualizing relationships between variables using seaborn plots (e.g., `jointplot`, `pairplot`, `lmplot`).
2. **Data Preprocessing**: Preparing the data for training by selecting the relevant features and splitting the dataset into training and testing sets.
3. **Modeling**: Training a Linear Regression model using `sklearn`.
4. **Evaluation**: Evaluating the model’s performance using metrics such as MAE, MSE, RMSE, and R² score.
5. **Conclusion**: Interpreting the model coefficients to provide recommendations for the company, focusing on mobile app development and membership retention.

## Key Insights
- **Mobile App** usage has a stronger influence on customer spending than the website.
- **Length of Membership** has the most significant impact on "Yearly Amount Spent", suggesting customer loyalty is crucial for boosting revenue.
- The model explains 98.9% of the variance in the target variable, showing a strong fit.

## Files
- The dataset used can be found here: [Ecommerce Customers Data](https://github.com/Saemfany/ecommerce_linear_regression/blob/ae50b42bd1ebb8338c077767c7c7db940f45e652/Ecommerce%20Customers).
- Python code and Jupyter notebooks for data analysis and model training are available in the [repository](https://github.com/Saemfany/ecommerce_linear_regression/blob/ae50b42bd1ebb8338c077767c7c7db940f45e652/Linear_Regression_Project.ipynb).
- Model results and insights are discussed in the [project report](https://github.com/Saemfany/ecommerce_linear_regression/blob/ae50b42bd1ebb8338c077767c7c7db940f45e652/Linear_Regression_Project.pdf).

#DataScience #MachineLearning #LinearRegression #Ecommerce #Python #DataAnalysis
