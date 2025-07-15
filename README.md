# Forecasting Foreign Tourist Arrivals and Their Economic Impact on India

## 📌 Overview
This project analyzes historical trends in **Foreign Tourist Arrivals (FTAs)** to India and evaluates their **economic impact** via **Foreign Exchange Earnings (FEE)**. Using publicly available datasets from [data.gov.in](https://data.gov.in), the project aims to derive actionable insights on **regional, demographic, and seasonal patterns** in tourism, while also predicting future FTAs using machine learning models.

---

## 🎯 Objectives
- Identify key regions contributing to FTAs and FEE over time.
- Analyze seasonal and age-group-wise distribution of FTAs.
- Forecast FTAs using time-series regression models.
- Understand the impact of COVID-19 on India's tourism sector.
- Recommend data-driven strategies to enhance India’s tourism competitiveness.

---

## 📊 Datasets
Sourced from: [data.gov.in](https://data.gov.in)

- **Continent and Country-wise FTAs** (2001–2021)
- **Quarterly FTAs** (2001–2019)
- **Age Group-wise FTAs** (2001–2019)
- **FEE due to Tourism** (2001–2023)
- **India’s Tourism Rank** (2001–2021)

---

## 🧹 Data Cleaning & Preprocessing
- Dropped irrelevant columns and handled missing values using **proportional imputation**.
- Conducted **Little's MCAR test** to determine the nature of missing data.
- Addressed outliers using **IQR analysis and box plots**.
- Feature Engineering:
  - `Year^2` (nonlinear trends)
  - `Lag features` (past trends)
  - `Rolling Mean (3-year)` (smooth temporal fluctuations)

---

## 📈 Methods & Tools
- **Languages**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Models Used**:
  - Linear Regression  
  - Random Forest Regressor  
  - Gradient Boosting Regressor  

- **Evaluation Metrics**:  
  - Mean Absolute Error (MAE)  
  - Mean Squared Error (MSE)  
  - R² Score

---

## 📌 Key Insights
- **Western Europe and West Asia** are the highest contributors to FTAs.
- **Middle-aged adults (25–54)** form the largest tourist group.
- **Quarterly analysis** shows seasonal peaks during winter months.
- **COVID-19 (2020–2021)** caused a sharp decline in both FTAs and FEE.
- **Gradient Boosting** provided the best predictive accuracy (R² ≈ 0.937).

---

## 📎 Conclusion
Our model forecasts future FTAs and identifies growth levers such as:
- Targeting high-potential regions.
- Optimizing seasonal promotions.
- Enhancing experiences for key demographics.

These insights can aid **policy makers** and **tourism planners** in boosting India's foreign tourism and associated economic gains.

---

## 👨‍💻 Contributors
- Madhav Kanjilimadom  
- Dishant Patel  
- Shravan Kakadiya

---


## ✅ Future Work
- Build an interactive dashboard using Power BI or Tableau (In Progress).
- Integrate additional features like visa policies, airline traffic, and hotel bookings.
- Apply deep learning models like LSTM for improved time-series forecasting.
