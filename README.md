# Mini-Project-CreditWise-Loan-System
CreditWise: Customer Credit Risk Prediction

##About the Project

Every day, banks and financial institutions receive thousands of loan applications. One of their biggest challenges is deciding whether an applicant is likely to repay the loan or become a defaulter. Making the wrong decision can result in significant financial losses.

I built CreditWise to explore how Machine Learning can assist in this decision-making process. The goal of the project is to predict whether a customer represents a good or bad credit risk based on their financial and personal information. Instead of relying only on manual evaluation, the model learns patterns from historical data and provides a prediction that can support credit approval decisions.

This project was developed as part of my learning journey in Machine Learning and Data Science. It covers the complete workflow of a real-world classification problem, from understanding the data to training and evaluating predictive models.

Problem Statement

Financial institutions need a reliable way to identify customers who are likely to repay their loans. Traditional manual assessment can be slow, subjective, and inconsistent.

The objective of this project is to build a Machine Learning model that can classify customers into two categories:

Good Credit Risk
Bad Credit Risk

Such predictions can help reduce loan defaults and improve the overall efficiency of the lending process.

Project Objectives

The main objectives of this project are:

Understand customer credit data.
Perform exploratory data analysis to identify important patterns.
Clean and preprocess the dataset.
Train Machine Learning models for credit risk prediction.
Compare model performance using evaluation metrics.
Predict the creditworthiness of new customers.
Dataset

The project uses a customer credit dataset containing information such as:

Customer age
Employment status
Annual income
Loan amount
Loan duration
Savings account details
Credit history
Housing information
Existing loans
Purpose of the loan

The target variable indicates whether the customer is considered a good or bad credit risk.

Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Scikit-learn
Project Workflow

#The project follows the standard Machine Learning pipeline.

###1. Data Collection

The dataset is imported into Jupyter Notebook using Pandas for further analysis.

###2. Data Exploration

Before building the model, I explored the dataset to understand:

Data types
Missing values
Feature distributions
Class balance
Relationships between variables

This step helped identify potential issues and understand the characteristics of the data.

###3. Data Preprocessing

The preprocessing stage includes:

Handling missing values
Removing duplicates
Encoding categorical variables
Preparing the dataset for model training

Proper preprocessing ensures that the Machine Learning algorithm receives clean and consistent data.

###4. Exploratory Data Analysis (EDA)

EDA was performed to discover meaningful insights about customer behavior.

Visualizations helped answer questions such as:

Which customers are more likely to default?
Which features have the strongest relationship with credit risk?
How is the target variable distributed?

###5. Model Training

After preprocessing, the dataset was divided into training and testing sets.

Different Machine Learning algorithms can be trained on the processed data to classify customer credit risk. The trained model learns patterns from historical records and uses those patterns to predict the creditworthiness of unseen customers.

###6. Model Evaluation

To evaluate the performance of the model, multiple classification metrics are used, including:

Accuracy
Precision
Recall
F1 Score
Confusion Matrix
ROC-AUC Score

These metrics provide a better understanding of how well the model performs on unseen data.
