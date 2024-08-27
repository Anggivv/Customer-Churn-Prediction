# Customer-Churn

## Introduction
The company has a dataset named Telco Customer Churn, which contains data on customer churn behavior. Each row in this dataset represents a customer's data, and each column contains information about the habits of each customer. The dataset consists of training data and test data. The training data is used for modeling, while the test data is used for making predictions.

## Goal
To predict customer churn so that the company can develop business strategies to retain customers.

## Step-by-Step Process
#### 1. Import Data and Data Identification:
* Import Data: Load the dataset into your working environment.
* Data Identification: Read and display the dataset to understand its structure and content, and show detailed information about the dataset, such as data types, missing values, and summary statistics.

#### 2. Exploratory Data Analysis (EDA):
* Categorical and Numerical Data Separation: Divide the dataset into categorical and numerical features to facilitate analysis.
* Check Missing Values: Identify and assess the extent of missing data in the dataset.
* Simple Visualization: Create basic plots to visualize distributions and relationships within the data, helping to uncover patterns and trends.

#### 3. Data Pre-Processing:
* Check for Duplicates: Identify and handle any duplicate records in the dataset to ensure data integrity.
* Remove Unnecessary Columns: Eliminate columns that are not needed for the analysis to streamline the dataset.
* Data Mapping: Perform mapping to convert categorical variables into numerical format if necessary for model compatibility.
* Check for Outliers: Detect and address any outliers that may affect the model's performance.

#### 4. Modelling:
* Model Training: Use decision tree and random forest algorithms to build predictive models based on the training data.
* Model Comparison: Evaluate and compare the performance of the decision tree and random forest models to determine which is more effective for predicting customer churn.

#### 5. Prediction:
* Testing and Evaluation: Apply the trained models to the test data to make predictions. Evaluate the model’s performance using appropriate metrics to assess its accuracy and effectiveness in predicting customer churn.

## Conclusion:
The project successfully developed a machine learning model capable of predicting customer churn with good accuracy. This final model can be utilized by the company to identify at-risk customers, enabling targeted interventions that may help reduce the churn rate.
