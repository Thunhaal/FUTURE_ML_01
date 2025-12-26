# Task 01 – Sales Forecasting (Machine Learning Internship – Future Interns)

This repository contains Task-01 of the Machine Learning Internship at **Future Interns**.  
The objective is to perform **time-series sales forecasting** using Instax camera sales transactions, visualize historical sales trends, and predict future demand using machine-learning models.

---

## 📌 Project Overview

Organizations rely heavily on **data-driven forecasting** for inventory planning, supply-chain optimization, and profitability.  
In this task, we:

- Processed Instax camera transaction dataset
- Aggregated daily sales totals
- Visualized trend & seasonal patterns
- Implemented **Facebook Prophet** forecasting model
- Generated **next-30-day sales predictions**

---

## 🧠 Machine Learning Workflow

| Step | Description |
|------|-------------|
| 1️⃣ Data Import & Cleaning | Loaded `.csv` files and handled missing data |
| 2️⃣ Feature Engineering | Converted invoice-level data → daily grouped totals |
| 3️⃣ Visualization | Trend & seasonal plots using Matplotlib |
| 4️⃣ Forecasting Model | Applied Prophet on historical daily sales |
| 5️⃣ Output | Predicted next 30 days & exported forecast |

---

## 🛠️ Tools & Technologies Used

| Category | Tools |
|----------|-------|
| Programming | Python |
| Libraries | Pandas, NumPy, Matplotlib, Prophet, Scikit-learn |
| Dashboard (Optional) | Power BI / Tableau |
| Notebook Environment | Google Colab |

---

## 📊 Output Screenshots

### 📈 Daily Sales Trend
![Daily Sales](Task_01_Sales_Forecasting/Daily_Sales.png)

Shows daily-level fluctuations and periodic demand peaks (especially around November–January).

---

### 🔮 30-Day Sales Forecast
![30-Day Forecast](Task_01_Sales_Forecasting/30_Day_Forecast.png)

Prophet forecast output with confidence range shading — clearly showing next-month seasonal demand.

---

## 📁 Repository Structure

