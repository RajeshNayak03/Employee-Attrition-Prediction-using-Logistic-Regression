# Employee Attrition Prediction using Logistic Regression

## Project Overview

Employee Attrition Prediction is a Machine Learning project that predicts whether an employee is likely to leave an organization based on various personal, professional, and workplace-related factors. The project utilizes Logistic Regression, a supervised learning classification algorithm, to identify patterns associated with employee turnover and provide actionable insights for improving employee retention.

## Problem Statement

Employee attrition is a major challenge for organizations as it impacts productivity, recruitment costs, and overall business performance. The objective of this project is to build a predictive model that can determine the likelihood of an employee leaving the company based on historical HR data.

## Dataset Information

The dataset contains employee-related information such as:

* Age
* Business Travel
* Daily Rate
* Department
* Distance From Home
* Education
* Education Field
* Job Role
* Job Satisfaction
* Monthly Income
* Overtime
* Work-Life Balance
* Years at Company
* Years in Current Role
* Years Since Last Promotion
* Years With Current Manager
* And several other HR-related attributes

### Target Variable

* Attrition = Yes (Employee Left)
* Attrition = No (Employee Stayed)

## Project Workflow

### 1. Data Collection

* Imported the HR Analytics dataset.
* Loaded the dataset using Pandas.

### 2. Data Preprocessing

* Checked dataset structure and data types.
* Handled missing values.
* Removed unnecessary columns such as Employee ID.
* Encoded categorical variables using Label Encoding.

### 3. Exploratory Data Analysis (EDA)

* Analyzed employee attrition patterns.
* Studied relationships between employee attributes and attrition.
* Generated visualizations using Matplotlib and Seaborn.
* Performed correlation analysis.

### 4. Feature Engineering

* Selected relevant features.
* Prepared the dataset for machine learning.

### 5. Model Building

* Split the dataset into training and testing sets.
* Implemented Logistic Regression using Scikit-Learn.
* Trained the model on historical employee data.

### 6. Model Evaluation

The model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1-Score

### 7. Prediction

The trained model can predict whether a new employee is likely to leave the organization based on their attributes.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## Machine Learning Algorithm

### Logistic Regression

Logistic Regression is a supervised learning classification algorithm used to predict binary outcomes. In this project, it is used to classify employees into:

* 0 → Employee Stays
* 1 → Employee Leaves

The algorithm calculates the probability of attrition and assigns the appropriate class label based on the prediction threshold.

## Key Learnings

Through this project, I gained practical experience in:

* Data Cleaning
* Missing Value Treatment
* Exploratory Data Analysis (EDA)
* Feature Selection
* Data Encoding Techniques
* Logistic Regression
* Classification Metrics
* Machine Learning Workflow
* Predictive Analytics

## Results

The model successfully predicts employee attrition and helps identify factors that influence employee turnover. These insights can assist organizations in making data-driven decisions to improve employee satisfaction and retention.

## Future Improvements

* Implement Decision Tree Classifier
* Apply Random Forest Classifier
* Compare multiple classification algorithms
* Perform Hyperparameter Tuning
* Deploy the model using Streamlit
* Create an interactive dashboard for HR Analytics

## Author

Rajesh Nayak

### Learning Journey

Recently completed Data Analytics fundamentals and currently progressing through Machine Learning algorithms. This project marks an important step in applying classification techniques to real-world business problems and building practical machine learning experience.

