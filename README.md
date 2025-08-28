# Air-Quality-Analysis-and-Prediction-Using-Machine-Learning

## 📌 Project Overview

This project explores and predicts **air quality trends** across five Ontario cities (Windsor, Hamilton Downtown, London, Sarnia, and Toronto) using **machine learning models**. With increasing urbanization and industrialization, air pollution (PM2.5, NO₂, O₃, etc.) poses significant health risks.

Our goal is to:

* Analyze **historical pollutant and weather data** (2021–2023).
* Predict **Air Quality Health Index (AQHI)** using advanced ML models.
* Support **public health systems** by providing actionable air quality forecasts.

This work aligns with the **WHO 2021 air quality guidelines**.

---

## 🔎 Research Questions

* What are the key **trends, seasonal variations, and meteorological impacts** on air quality?
* Can ML models accurately **forecast AQHI** categories (Low, Moderate, High)?
* How do city-specific factors (traffic, industry) affect air quality patterns?

---

## 📊 Dataset Information

* **Pollutant Data:** [Air Quality Ontario](https://www.airqualityontario.com/) (PM2.5, NO₂, O₃, etc.)
* **Weather Data:** [Environment Canada](https://climate.weather.gc.ca/) (Temperature, Humidity, etc.)
* **Timeframe:** January 2021 – December 2023
* **Coverage:** 5 Ontario cities
* **Volume:** \~26,280 hourly records per city
* **Data Cleaning:** Missing values imputed using rolling averages

---

## ⚙️ Methodology

1. **Data Preprocessing**

   * Outlier removal, missing value handling, normalization
2. **Exploratory Data Analysis (EDA)**

   * Time-series plots, correlation analysis, seasonal trends
3. **Feature Engineering**

   * Pollutant + weather features (PM2.5, O₃, NO₂, Temp, Humidity)
4. **Modeling**

   * Regression (XGBoost, LightGBM, CatBoost, Random Forest)
   * Classification of AQHI categories (Low: 1–3, Moderate: 4–6, High: 7+)
   * Forecasting pollutants using **ARIMA** models
5. **Validation Metrics**

   * Accuracy, RMSE, R²

---

## 📈 Key Insights

* **Regression Models**: Adding temperature improved Windsor’s accuracy from **60% → 66%**.
* **Classification Models**: Ensemble methods (**XGBoost, LightGBM, CatBoost**) achieved \~**90% accuracy**.
* **ARIMA Forecasting**: Successfully captured seasonal O₃ and NO₂ trends, but struggled with anomaly events (e.g., wildfire-driven PM2.5 spikes).
* **City-Specific Findings**:

  * Sarnia & Hamilton strongly impacted by industry.
  * Seasonal weather patterns influenced pollutant levels across all cities.

---

## 📊 Interactive Dashboards

We created dashboards to **visualize results** and make insights more accessible:

* **Air Quality Prediction Dashboard** – Visualizing AQHI classification and drawing insight from other variables affecting air quality.

---

## 🚀 Future Scope

* Integrate pollutant forecasts (ARIMA + ML) for hybrid modeling.
* Explore **deep learning models** (e.g., LSTMs, hybrid neural networks).
* Develop **real-time dashboards & mobile applications** for public use.
* Implement **AI-driven anomaly detection** for wildfire or extreme event predictions.

---

## 📚 Technologies Used

* **Languages:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, LightGBM, CatBoost, Statsmodels (ARIMA)
* **Visualization:** Matplotlib, Seaborn, Plotly, Tableau, Power BI
* **Dashboarding:** Streamlit, Interactive Tableau dashboard

---

## 🤝 Contributors

* Gowtham Chandu
* Sanjana Indu
* Venkata Dhanayya
* LingFang He
* **Kenechukwu Enem**

---

## 📜 License

This project is licensed under the MIT License.


Would you like me to also **add visual examples (charts/graphs screenshots)** to the README so it looks more engaging for GitHub viewers, or keep it text-only for now?
