# Bike-Sharing-Demand-Prediction-
# Project Summary
Regression analysis in machine learning gives us the relationship between the dependent and the independent variables. Regression analysis provides information such as how the dependent variable changes with the change in the independent variables.

Regression analysis is a predictive analysis in machine learning, where the algorithms try to understand the relationship between the dependent and independent variables to predict unseen data. The regression model tries to pick the best fit line through the given dependent variables to predict the outcome. The assumptions in the regression analysis are

* The relationship between the independent and dependent variables is linear.
* There is no multicollinearity between the independent variables.
* The errors should follow a normal distribution.
* There should be homoscedasticity of errors or residuals. The variance should be almost the same at every point of the line.
In this project, we are doing a regression analysis of the Seoul bike rental data to predict the count of bikes rented with the help of the dependent variables in the dataset. The data set contains pieces of information such as the rented bike count, hour, season, temperature, humidity, holiday, functioning day, etc.,

# Problem Statement
Nowadays, rental bikes are introduced in many urban cities to enhance mobility comfort and for an easier commute. Availability and accessibility of bikes should be easier for the public, and the waiting time should be less. The crucial part is to analyze the demand and provide the bikes as per the need. To make the process smooth and hassle-free, we should predict the bike demands for different hours of the day. By implementing machine-learning models to the Seoul bike rental data set, we try to predict the bike demands at various hours of the day.

# Steps involved in Bike-Sharing-Demand-Prediction
The dependent or the target variable for the regression analysis is the rented bike count. We are trying to train our model to learn the patterns inside the data and to predict the outcome accordingly.

The different steps involved in this Regression project are 
* Exploratory Data Analysis
* Feature selection and data preprocessing
* Scaling of variables
* Model implementation
* Linear Regression
* Lasso Regression
* Ridge Regression
* ElasticNet Regression
* Decision Tree Regressor
* Random Forest Regression
* Gradient Boost Regression
* XGB REgression
* Cross Validation and hyperparameters

---



**Exploratory Data Analysis -**
 	In EDA, we will deal with the missing and duplicates in the dataset. We look deeper into the variables and their relationships with each other.

   ---

**Feature Selection and Data preprocessing-**
	Data preprocessing is to look into multicollinearity between the independent variables and drop the unimportant feature. We split the variables using train_test_split to see how the model performs and predict errors for the unseen data. 

---
**Feature Scaling -**
	Feature Scaling is a technique to bring the values into a particular range. Feature scaling helps the gradient descent reach the cost function minima easier than with the unscaled values. There are two types of scalings are
* Normalization - Uses min and max values
* Standardization - Uses mean and standard deviation
---
**Model implementation -** In this project, we will implement Linear Regression, lasso regression, Ridge regression, elastic net Regression, Decision Tree , Random Forest Regression, Gradient Boost Regression, and XGB Regression. By looking into their model errors, we try to conclude.
	
---
**Cross Validation and hyperparameters**
	In the train test split, train and test data is split on a ratio and pushed into the model, where there is a possibility for inaccurate prediction. So we use cross-validation, where the data is divided into different subsets and tested multiple times.
