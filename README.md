# SyriaTel Customer Churn Prediction

## Project Overview

This project aims to build a classification model to predict whether a customer will "soon" stop doing business with SyriaTel, a telecommunications company. The main objectives of this project are to reduce customer churn, increase revenue, enhance customer satisfaction, and optimize marketing strategies by identifying customers who are likely to churn.

## Business Objectives

1. **Reduce Customer Churn:** Identify customers who are likely to churn, enabling the company to take proactive measures to retain them.
2. **Increase Revenue:** Maintain a stable customer base, increasing customer lifetime value (CLTV) and overall revenue.
3. **Enhance Customer Satisfaction:** Understand the reasons behind customer churn and address underlying issues.
4. **Optimize Marketing Strategies:** Create more effective and targeted marketing strategies focused on customers who are at risk of leaving.

## Dataset

The dataset used in this project is provided by SyriaTel and contains various customer features such as account length, customer service calls, total charges, etc., along with the target variable indicating whether the customer churned (`churn`).

## Project Structure

1. **Importing Libraries and Packages**
    - Required libraries such as `pandas`, `numpy`, `matplotlib`, `seaborn`, and machine learning libraries like `sklearn` are imported.

2. **Data Loading**
    - The dataset is loaded using `pandas` and the first few rows are inspected to understand the structure.

3. **Data Cleaning**
    - Missing values and duplicates are handled, ensuring a clean dataset for analysis.

4. **Exploratory Data Analysis (EDA)**
    - Univariate and bivariate analyses are performed to understand the distribution of features and their relationship with the target variable (`churn`).
    - ![image](https://github.com/user-attachments/assets/770ab403-efaf-4e5b-822c-9502011a9950)

    - Correlation matrices and visualizations are used to identify important features.
![image](https://github.com/user-attachments/assets/7a6d383a-17fb-4217-8618-2765b5ed2743)


5. **Feature Engineering**
    - The dataset is prepared for modeling by encoding categorical variables, scaling numerical features, and splitting the data into training and testing sets.

6. **Modeling**
    - Several classification models are built including Logistic Regression, Decision Tree, and Random Forest.
    - The models are trained on the training set and predictions are made on the test set.

7. **Model Evaluation**
    - The performance of the models is evaluated using metrics such as accuracy, confusion matrix, and classification report.
    - ![image](https://github.com/user-attachments/assets/afaa3af1-1f96-4717-b82b-83ec84536ef2)


8. **Hyperparameter Tuning**
    - Grid search is performed to find the best hyperparameters for the Random Forest model, optimizing its performance.

9. **Future Predictions**
    - The best model is used to predict customer churn on new data.

10. **Conclusion**
    - Based on the model evaluation, recommendations are made on how SyriaTel can reduce customer churn and enhance customer satisfaction.

