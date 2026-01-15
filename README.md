🛒 Walmart Store Sales Forecasting (Time Series Analysis)
📌 Project Overview

This project focuses on forecasting weekly sales for Walmart stores using historical sales data.
Accurate sales forecasting helps retailers optimize inventory management, staffing, and supply chain planning.

In this project, I performed end-to-end time series analysis, including data preprocessing, exploratory data analysis (EDA), model building, evaluation, and future forecasting.

🎯 Objectives

Analyze historical Walmart sales data

Identify trends, seasonality, and holiday effects

Build a time series forecasting model (ARIMA)

Evaluate model performance using standard metrics

Forecast future sales to support business decisions

📂 Dataset Description

The dataset is taken from the Walmart Recruiting – Store Sales Forecasting competition on Kaggle.

Files Used

train.csv – Historical weekly sales data

test.csv – Future dates for prediction

features.csv – Additional features (temperature, fuel price, holidays, etc.)

stores.csv – Store type and size information

Target Variable

Weekly_Sales

Time Variable

Date

🛠️ Tech Stack & Tools

Programming Language: Python

Libraries:

pandas, numpy

matplotlib, seaborn

scikit-learn

statsmodels (ARIMA)

Environment: Jupyter Notebook

📁 Project Structure
walmart-sales-forecasting/
│
├── data/
│   ├── train.csv
│   ├── test.csv
│   ├── features.csv
│   ├── stores.csv
│
├── notebooks/
│   └── walmart_sales_forecasting.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore

🔎 Exploratory Data Analysis (EDA)

Key insights from EDA:

Weekly sales show clear seasonal patterns

Holiday weeks significantly impact sales volume

Sales trends vary over time, highlighting the importance of time-aware models

Visualizations include:

Total weekly sales trend over time

Holiday vs non-holiday sales comparison

🤖 Model Building

Aggregated weekly sales across all stores

Performed time-based train-test split

Built an ARIMA (AutoRegressive Integrated Moving Average) model

Generated forecasts for future weeks

📏 Model Evaluation

The model was evaluated using:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

These metrics help measure the accuracy of sales predictions compared to actual values.

🔮 Forecasting Results

Successfully forecasted weekly sales for upcoming periods

Forecast captures overall trend and seasonality

Results can assist Walmart in inventory and demand planning

📊 Visual Results

The project includes visual comparisons of:

Training data

Actual test data

Forecasted sales

This helps clearly understand model performance.

💡 Business Insights

Sales increase significantly during holiday periods

Time series forecasting can improve operational efficiency

Accurate forecasts support better decision-making in retail planning

▶️ How to Run This Project

Clone the repository

Install dependencies:

pip install -r requirements.txt


Open Jupyter Notebook:

jupyter notebook


Run walmart_sales_forecasting.ipynb

📌 Future Improvements

Add Facebook Prophet for better seasonality handling

Forecast sales at store/department level

Deploy the model using Streamlit

👤 Author

Ashanur
Data Science & Machine Learning Student