# Bank Telemarketing Success Prediction with Logistic Regression

This project aims to predict the success of bank telemarketing campaigns by analyzing a dataset of customer information and campaign history. The project employs logistic regression, a supervised machine learning algorithm, to build a predictive model that can identify potential subscribers to bank term deposits.

## Problem Statement

A Portuguese banking institution seeks to enhance the effectiveness of its telemarketing campaigns by identifying individuals who are more likely to subscribe to bank term deposits. This project focuses on developing a predictive model that can anticipate customer behavior based on various demographic, economic, and campaign-related factors.

## Dataset Description

The dataset utilized in this project comprises 41188 instances, each representing a customer's interaction with the bank's telemarketing campaigns. The dataset encompasses 21 attributes, including:

* **Customer Information:**
    * Age
    * Job type
    * Marital status
    * Education level
    * Credit default status
    * Housing loan status
    * Personal loan status

* **Campaign History:**
    * Contact communication type (cellular or telephone)
    * Last contact month
    * Last contact day of the week
    * Last contact duration (seconds)
    * Number of contacts during the current campaign
    * Number of days since last contact from a previous campaign
    * Number of contacts prior to the current campaign
    * Outcome of the previous marketing campaign

* **Socioeconomic Context:**
    * Employment variation rate
    * Consumer price index
    * Consumer confidence index
    * Euribor 3-month rate
    * Number of employed individuals

* **Target Variable:**
    * Whether the customer subscribed to a term deposit (yes or no)

## Methodology

The project adheres to a structured machine learning approach, encompassing the following steps:

1. **Data Exploration and Preprocessing:**
    * Analyzing data distribution and identify missing values
    * Handling missing values using appropriate techniques
    * Transforming categorical variables into numerical representations

2. **Feature Engineering:**
    * Applying Principal Component Analysis (PCA) to reduce dimensionality and mitigate multicollinearity
    * Creating new features based on existing attributes

3. **Feature Selection:**
    * Employing correlation analysis and feature importance measures to select relevant features
    * Removing redundant or highly correlated features to enhance model performance

4. **Model Training and Evaluation:**
    * Splitting the dataset into training and testing sets
    * Training a logistic regression model on the training set
    * Evaluating the model's performance on the testing set using metrics such as accuracy, precision, recall, and F1-score

5. **Model Visualization:**
    * Visualizing the confusion matrix and ROC curve to assess the model's performance

## Results

The project's findings indicate that logistic regression is an effective algorithm for predicting the success of bank telemarketing campaigns. The trained model achieves an accuracy of 90% on the testing set, implying that it can correctly classify 90% of the clients. The model's performance is further validated by the confusion matrix and ROC curve, which demonstrate its ability to accurately distinguish between subscribers and non-subscribers.

## Conclusion

This project successfully demonstrates the application of logistic regression in predicting the success of bank telemarketing campaigns. The developed model can be utilized by the banking institution to identify potential subscribers, optimize their telemarketing strategies, and enhance customer engagement. The project also highlights the importance of data analysis, feature engineering, and model evaluation in achieving robust and reliable predictive modeling.

## Dataset source

https://archive.ics.uci.edu/dataset/222/bank+marketing
