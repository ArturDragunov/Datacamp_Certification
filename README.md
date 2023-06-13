# datacamp_certification
Datacamp Data Scientist Professional Certification  
📝 Task List  
Your written report should include both code, output and written text summaries of the following:  

Data Validation:  
Describe validation and cleaning steps for every column in the data  
Exploratory Analysis:  
Include two different graphics showing single variables only to demonstrate the characteristics of data  
Include at least one graphic showing two or more variables to represent the relationship between features  
Describe your findings  
Model Development  
Include your reasons for selecting the models you use as well as a statement of the problem type  
Code to fit the baseline and comparison models  
Model Evaluation  
Describe the performance of the two models based on an appropriate metric  
Business Metrics  
Define a way to compare your model performance to the business  
Describe how your models perform using this approach  
Final summary including recommendations that the business should undertake  


# Recipe Traffic Predictor  
This repository contains a Machine Learning model that predicts whether a recipe will attract high web traffic based on a variety of factors including the calories, carbohydrates, sugar, and protein in the recipe, as well as the category of the recipe and the number of servings it makes.  

## Introduction
This project aimed to build a machine learning model that could accurately predict which recipes will be popular at least 80% of the time. The model was built using a dataset consisting of 947 rows and 8 columns. Each row represented a unique recipe, and the columns represented various attributes of each recipe, including their nutritional content, the number of servings they make, and their categorization.

## Data Validation
The dataset underwent a thorough cleaning and validation process before being used for exploratory data analysis. All variables were validated, and several modifications were deemed necessary. Please refer to the full report for detailed observations and steps taken for each variable.

## Exploratory Data Analysis
The target variable and features of the recipe were investigated, and the relationship between the target variable and features was analyzed. This led to the decision to apply Yeo-Johnson transformation to normalize the numeric variables.

## Model Fitting & Evaluation
The problem of classifying recipes into high or low traffic categories was tackled using two parametric models: Logistic Regression and Linear Discriminant Analysis. The model evaluation was based on two metrics: Overall Accuracy and False Positive rate. The models were trained and evaluated using a split of the data into training and testing sets.

## Results
The Logistic Regression model was recommended due to its performance, interpretability, and robustness. However, the Linear Discriminant Analysis Model was also found to be a strong contender and may be worth considering as an alternative.

## Recommendations
The logistic regression model, with a precision of 91%, can be used to accurately identify high-traffic recipes and help increase site traffic. To evaluate the real-world applicability of the model, it is suggested to conduct an A/B test. Additionally, the model can be improved by collecting more data and engaging in feature engineering. It's also important to continuously monitor the model's performance after implementation.

## Prerequisites
Before running the code, you'll need to have Python and the following libraries installed:

Pandas
NumPy
Sci-kit Learn
Matplotlib
Seaborn
Scipy  

## Instructions
To get started with the project:

Clone the repository: git clone https://github.com/ArturDragunov/Datacamp_Certification.git
Navigate to the project directory: cd recipe-traffic-predictor
Run the Jupyter notebook

## Files
Datacamp Data Scientist Professional Certification.ipynb: This Jupyter notebook contains the solution text and code for the project.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details

## Contact
If you have any questions, feel free to open an issue or pull request.

## Acknowledgments
OpenAI for GPT-4
Python
The entire open-source community
