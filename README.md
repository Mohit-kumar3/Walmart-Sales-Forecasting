# Walmart-Sales-Forecasting
**Overview**

Sales forecasting is estimating the future sales of a product or service. It is a crucial part of any company and its business plan, as it helps businesses make informed decisions about resource allocation, marketing strategy, and investment. Walmart is one of the largest retail companies in the world, and it uses various sales forecasting methods, such as time series analysis, regression analysis, etc., to inform its business decisions. In this, we will apply regression analysis for sales forecasting on a dataset provided by Walmart.

**What are We Building?**

In this project, we will use Walmart's weekly sales data. It consists of historical sales data for 45 Walmart stores in different regions. Each store contains several departments, and our objective is to predict the department-wide sales for each store. We will apply regression analysis to forecast the sales for each department based on multiple factors, such as temperature, fuel price, store type, CPI, employment index, etc.

**Pre-requisites**

Python

Data Visualization

Descriptive Statistics

Machine Learning

Data Cleaning and Preprocessing


**How Are We Going to Build This?**

We will handle missing values present in the dataset during the data-cleaning stage.
We will perform exploratory data analysis (EDA) using various visualization techniques to identify underlying patterns and correlations that can help us derive insights.
Further, we will train and develop multiple regressor ML models, such as the KNN, Decision Tree, Random Forest, and XGBoost Regressor,models, and compare their performance based on the model’s accuracy and RMSE.


**Requirements**

We will be using below libraries, tools, and modules in this project:

Pandas

Numpy

Matplotlib

Seaborn

Sklearn

xgboost


**Dataset Feature Descriptions**

This dataset contains three different CSVs. Let’s understand a brief description of each feature below -

1. Stores.csv - This file contains information about the 45 stores, indicating their type and size.

2. Train.csv - It contains each department's historical weekly sales data. It contains the following features -

        Store - the store number.

        Dept - the department number.

        Date - the week.

        Weekly_Sales - sales for the given department in the given store.

        IsHoliday - whether the week is a special holiday week.


3. Features.csv - It contains additional features regarding the store, as mentioned below -

        Store - the store number.

        Date - the week.

        Temperature - the average temperature in the region.

        Fuel_Price - the cost of fuel in the region.

        MarkDown1-5 - anonymized data related to promotional markdowns. It is only available after Nov 2011 and is not available for all stores all the time.

        CPI - the consumer price index.

        Unemployment - the unemployment rate.

        IsHoliday - whether the week is a special holiday week.
