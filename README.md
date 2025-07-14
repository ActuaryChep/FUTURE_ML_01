 This project demonstrates how to use an ARIMA (AutoRegressive Integrated Moving Average) model to forecast monthly retail sales from historical transaction data. It is ideal for data science and analytics portfolios targeting roles in business intelligence, forecasting, and retail analytics.
 
 Project Objective
 
To build a time series forecasting model that predicts future monthly sales using historical sales data. This helps businesses plan inventory, optimize pricing, and prepare for seasonal demand shifts.
The dataset contains daily sales transactions, including: Date of transaction,Units sold (sales),Inventory on hand and Price per unit. The data was resampled to monthly sales totals for forecasting
Model Workflow

1.	Data Cleaning
   
Convert date strings to datetime format

Set date as index

Resample daily sales into monthly totals

2. Train-Test Split
   
Use all but the last 6 months for training

Reserve the last 6 months for testing

3. ARIMA Modeling

Fit an ARIMA(1,1,1) model

Forecast the next 6 months

4.	Evaluation
	
Measure accuracy using RMSE (Root Mean Squared Error)

Visualize actual vs forecasted sales
