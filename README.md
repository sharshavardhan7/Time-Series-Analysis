
![Python](https://img.shields.io/badge/python-3.10-blue)




Data Set Link :https://www.kaggle.com/datasets/abdullahmeo/e-commerce-sales-analysis-junior-analyst/data

📌 Project Overview

In today’s competitive e-commerce environment, understanding historical sales patterns is critical for data-driven decision making. This project performs an end-to-end time series analysis on simulated e-commerce sales data to identify trends, evaluate product and category performance, and forecast future sales using classical statistical models.

The focus of this project is not only on building models, but also on deriving actionable business insights that can help management optimize pricing, inventory, and regional strategies.

🎯 Business Objective

The primary objectives of this project are:

Analyze historical sales trends over time

Identify top-performing products and categories

Detect the “High Sales, Low Profit” pattern for profitability improvement

Forecast future sales using Autoregressive (AR) and Moving Average (MA) models

📂 Dataset Description

The dataset contains 3,500 historical e-commerce transactions with the following attributes:

Order Date – Date of the transaction (used for time series analysis)

Product Name – Individual product identifier

Category – Product category (e.g., Electronics, Office, Accessories)

Region – Sales region

Quantity – Number of units sold

Sales – Total sales value

Profit – Profit earned from the transaction

🔄 Project Workflow

This project follows a complete end-to-end data science workflow:

Data Cleaning & Preprocessing

Converted date fields to datetime format

Sorted records chronologically

Derived time-based features such as Month and Year

Exploratory Data Analysis (EDA)

Visualized monthly sales trends

Identified seasonality and fluctuations in sales

Business Insights

Ranked top-selling products by revenue

Analyzed category-wise sales vs profit to identify low-margin segments

Time Series Preparation

Aggregated transactional data into monthly sales

Checked stationarity using the Augmented Dickey-Fuller (ADF) test

Applied differencing where required

Modeling

Built Autoregressive (AR) model to capture dependency on past sales

Built Moving Average (MA) model to capture short-term fluctuations

Model Evaluation

Evaluated models using MAE and RMSE

Compared AR and MA model performance visually and numerically

📈 Key Results & Insights

The MA model performed better for short-term forecasting by capturing sudden sales fluctuations.

The AR model provided smoother predictions, reflecting long-term sales dependency.

Certain product categories showed high sales but comparatively low profit, indicating opportunities for pricing and cost optimization.

Monthly sales trends revealed seasonal patterns useful for inventory planning.

🛠️ Technologies Used

Python

Pandas & NumPy – Data manipulation

Matplotlib – Data visualization

Statsmodels – Time series modeling (AR & MA)

Scikit-learn – Model evaluation metrics

🚀 Future Improvements

Extend models to ARMA / ARIMA

Incorporate seasonality using SARIMA

Build region-wise or category-wise forecasts

Deploy forecasts through a dashboard

👤 Author

Harshavardhan Siliveru
M.Tech (Data Science)

