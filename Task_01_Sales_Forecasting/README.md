# Task 01 – Sales Forecasting (Machine Learning Internship – Future Interns)

This repository contains Task-01 of the Machine Learning Internship at **Future Interns**.  
The objective of this task is to perform **time-series sales forecasting** using a dataset of Instax camera transactions, visualize key trends, and predict future demand using machine-learning techniques.

---

## 📌 Project Overview

Organizations rely heavily on **data-driven demand forecasting** to optimize inventory, supply chain planning, and revenue strategy.  
In this task, we:

- Processed Instax camera sales transaction data
- Aggregated daily sales totals
- Visualized sales trend and seasonality
- Built a **time-series forecasting model** using **Facebook Prophet**
- Predicted the next **30-days of future sales**

---

## 🧠 Machine Learning Approach

| Step | Description |
|------|-------------|
| 1️⃣ Data Import & Cleaning | Loaded `.csv` data & removed null values |
| 2️⃣ Feature Engineering | Converted invoice dates → daily aggregated sales |
| 3️⃣ Visualization | Trend plots using Matplotlib |
| 4️⃣ Forecast Model | Prophet model fitted on daily sales |
| 5️⃣ Output | 30-day forecast generated & visualized |

---

## 🛠️ Tools & Technologies Used

| Category | Tools |
|----------|-------|
| Programming | Python |
| Libraries | Pandas, NumPy, Matplotlib, Prophet, Scikit-learn |
| Optional BI | Power BI / Tableau (for dashboarding) |
| Notebook Environment | Google Colab |

---

## 📊 Output Screenshots

### 📈 Daily Sales Trend
![Daily Sales](Task_01_Sales_Forecasting/Daily_Sales.png)

This graph shows day-to-day sales volume across the dataset.  
A clear **pattern of fluctuations and seasonal peaks** (especially around December–January & festival periods) can be seen.

---

### 🔮 30-Day Sales Forecast
![30-Day Forecast](Task_01_Sales_Forecasting/30_Day_Forecast.png)

The **Prophet model** predicts future demand for the next 30 days.  
The shaded confidence interval helps visualize expected range variability.  
Results indicate continued seasonal spikes and demand growth.

---

## 📁 Repository Structure


---

## 📝 Conclusions & Learnings

From this task, I learned:

- How to perform **time-series forecasting** using Prophet
- Importance of **data cleaning & aggregation**
- How visualizations reveal **seasonality patterns**
- Forecasting helps businesses plan **inventory, marketing & resource allocation**

---

## 🚀 Future Improvements

| Improvement | Plan |
|-------------|------|
| Add dashboard | Deploy insights in Power BI/Tableau |
| Add model comparison | ARIMA vs Prophet vs LSTM |
| Productionization | Deploy forecast API using Flask |

---

## 🙋‍♂️ Author

**S. T. Thunhaal**  
Machine Learning Intern – Future Interns  
LinkedIn: _add link here_

---

