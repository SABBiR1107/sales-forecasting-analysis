# 🛒 Walmart Store Sales Forecasting (Time Series Analysis)

## 📌 Project Overview
This project focuses on forecasting **weekly sales for Walmart stores** using historical retail data.  
Accurate sales forecasting helps businesses optimize **inventory management, staffing, and supply chain planning**.

The project demonstrates an **end-to-end time series workflow**, including data preprocessing, exploratory data analysis (EDA), modeling, evaluation, and future forecasting.

---

## 🎯 Objectives
- Analyze historical Walmart sales data
- Identify trends, seasonality, and holiday effects
- Build a time series forecasting model (ARIMA)
- Evaluate model performance using standard metrics
- Forecast future weekly sales to support business decisions

---

## 📂 Dataset Description
Dataset source:  
**Walmart Recruiting – Store Sales Forecasting (Kaggle)**

### Files Used
- `train.csv` – Historical weekly sales data
- `test.csv` – Future dates for prediction
- `features.csv` – Additional features (temperature, fuel price, CPI, holidays)
- `stores.csv` – Store type and size information

### Target Variable
- **Weekly_Sales**

### Time Variable
- **Date**

---

## 🛠️ Tech Stack & Tools
- **Programming Language:** Python  
- **Libraries:**  
  - pandas, numpy  
  - matplotlib, seaborn  
  - scikit-learn  
  - statsmodels (ARIMA)  
- **Environment:** Jupyter Notebook

---

## 📁 Project Structure
walmart-sales-forecasting/
│
├── data/
│ ├── train.csv
│ ├── test.csv
│ ├── features.csv
│ ├── stores.csv
│
├── notebooks/
│ └── walmart_sales_forecasting.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore


---

## 🔎 Exploratory Data Analysis (EDA)
Key insights from EDA:
- Weekly sales show clear **seasonal patterns**
- **Holiday weeks significantly impact sales volume**
- Sales trends vary over time, highlighting the need for time-aware models

### Visualizations:
- Total weekly sales trend over time
- Holiday vs non-holiday sales comparison

---

## 🤖 Model Building
- Aggregated weekly sales across all stores
- Converted date column to datetime format
- Performed **time-based train-test split**
- Built an **ARIMA (AutoRegressive Integrated Moving Average)** model
- Generated forecasts for future weeks

---

## 📏 Model Evaluation
The model was evaluated using:
- **MAE** – Mean Absolute Error
- **RMSE** – Root Mean Squared Error
- **MAPE** – Mean Absolute Percentage Error

Residual diagnostics were also performed to ensure model stability.

---

## 🔮 Forecasting Results
- Successfully forecasted weekly sales for future periods
- Forecast captures overall **trend and seasonality**
- Useful for demand planning and inventory optimization

---

## 💡 Business Insights
- Sales increase significantly during holiday periods
- Time series forecasting improves retail planning efficiency
- Accurate forecasts support better operational decisions

---

## ▶️ How to Run This Project

1. Clone the repository:
```bash
2. git clone <your-repo-link>

Install dependencies:

pip install -r requirements.txt


3. Open Jupyter Notebook:

jupyter notebook


4. Run:

notebooks/walmart_sales_forecasting.ipynb
