# Predicting-future-sales

A Russian software firm - 1C Company, has provided a time series data set consisting of daily sales data. We plan to create machine learning models to help predict subsequent month data for a particular product at a particular shop. This model would help the company know how much inventory they will need for next month.

## Methodology

For Russian Software Company-1c, we are given the task of projecting total sales for each product category and store in the coming month. We started with Exploratory Data Analysis which helped us to do the initial investigations on data and it will also help us discover patterns, to spot anomalies and to test hypotheses. After performing EDA, we used different models to identify which model gives the best accuracy for predicting the sales. We first used XGBoost since it is very good at identifying patterns in data. We also used SARIMA and ARIMA which are statistical analysis models for forecasting future trends. We also used Prophet which is a procedure for forecasting time series data based on an additive model where nonlinear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. We used Python for coding, and the essential libraries will be Pandas, Numpy, Sklearn, and Data visualization packages like Seaborn and Matplotlib.

## Implementation

[Kaggle Dataset](https://www.kaggle.com/c/competitive-data-science-predict-future-sales/data)

**Dataset consists of daily historical sales data of 1C Company. Data set provided includes sales information across 60 shops, 214200 items over a period of 34 months**

## Data Preparation and Cleaning:

**Step 1**: Check whether data is cross sectional, time series or transactional
According to our data analysis, our data is transactional data since we have a time series variable and there are other variables as well. A data is called transactional data when the target variable is dependent on time and there are other variables on which the predicted value is not dependent on.

**Step 2**: If the data is transactional then convert it into time series data
For this we took an aggregate on the item count column to find sum of items sold on each day

**Step 3**: Time series is stationary or not

Statistical modeling methods assume or require the time series to be stationary.
For a time series to be stationary, the mean should be constant and so should the variance and there should be no seasonality in data 
To check whether our time series data is stationary or not we used the Augmented Dickey Fuller Test.

**Null Hypothesis** : time series is non-stationary
**Alternate Hypothesis**: time series is stationary. It does not have time-dependent structure



![image](https://drive.google.com/uc?export=view&id=1Tkezaav31oyI9z-NREQci6YIHAtUqSPF)

# Forecasting Future Sales

## XGBoost

![image](https://drive.google.com/uc?export=view&id=1aZnpi7Cl9F4K92aMjrA-LmSyIyj_BOt0)

## ARIMA

![image](https://drive.google.com/uc?export=view&id=1l1Uo2jFDMg-3ewTB4YDyuZ91tRZof5AB)

## SARIMAX

![image](https://drive.google.com/uc?export=view&id=1DySnL5UGHzM8MKjId-XVcH7xYU3-aDhY)

## FBPROPHET

![img](https://drive.google.com/uc?export=view&id=1HYLYfNhtfIYbSQSrl5BmhgjBOKpCAhXW)


# Future Scope

![img](https://drive.google.com/uc?export=view&id=1E4QjizSmRtBjxqFEoycNKtpZdx6ypZzs)


