# Car-Insurance-Prediction-Using-Machine-Learning
## Project Overview

This project aims to predict whether a customer will purchase car insurance using machine learning techniques. The dataset contains information about personal demographics, financial status, and marketing campaign interactions. The goal is to build a classification model that can accurately identify potential customers who are likely to purchase insurance.

## Problem Statement

Insurance companies invest heavily in marketing campaigns to attract customers. Predicting which customers are most likely to respond positively can help optimize resources, reduce marketing costs, and improve overall efficiency. This project uses historical campaign data to build a predictive model for car insurance subscription.

## Objective

- Perform data preprocessing including handling of missing values and outliers.
- Conduct exploratory data analysis (EDA) to uncover patterns and trends.
- Engineer relevant features and encode categorical variables appropriately.
- Train multiple machine learning models for binary classification.
- Evaluate and tune the models to achieve the best performance.
- Compare models and select the most effective one.

## Dataset Description

The dataset consists of 4000 records and 19 features. The key features include:

- **Age**: Age of the customer
- **Job**: Type of job (categorical)
- **Marital**: Marital status
- **Education**: Level of education
- **Default**: Credit default status (binary)
- **Balance**: Customer's account balance
- **HHInsurance**: Household insurance indicator (binary)
- **CarLoan**: Car loan indicator (binary)
- **Communication**: Type of communication during campaign
- **LastContactDay/Month**: Last contact date
- **NoOfContacts**: Number of contacts during the campaign
- **DaysPassed/PrevAttempts**: Previous campaign performance
- **CallStart/CallEnd**: Call time (dropped during preprocessing)
- **CarInsurance**: Target variable (0 = No, 1 = Yes)

## Techniques Used

- Data Cleaning and Preprocessing
- Outlier Detection and Handling
- Encoding of Categorical Variables
- Data Visualization (histograms, box plots, heatmaps, pair plots)
- Logistic Regression, K-Nearest Neighbors (KNN), Random Forest
- Hyperparameter Tuning using GridSearchCV
- Model Evaluation using Accuracy, Precision, Recall, F1-score, and Confusion Matrix

## Results

- Logistic Regression performed best with an accuracy of around 97%.
- Random Forest and KNN were also evaluated, but logistic regression provided the most balanced and interpretable results.

## Conclusion

This project demonstrates a complete pipeline for a binary classification task using real-world data. The logistic regression model provides a strong baseline and performs well, showing the importance of thorough data cleaning, visualization, and model tuning.
