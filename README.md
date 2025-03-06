
# 🌦️ Weather Trend Forecasting Project

This project analyzes the **"Global Weather Repository"** dataset to forecast weather trends, conduct exploratory analysis, perform advanced analysis, and provide actionable insights.

---

## 🎯 PM Accelerator Mission:

**"PM Accelerator's mission is to empower professionals by providing targeted learning experiences, practical insights, and relevant knowledge to accelerate career growth."**

---

## 🗃 Dataset Description:

The dataset contains global daily weather data with over 40 columns including temperature, precipitation, humidity, wind conditions, and air quality metrics.

**Source:** [Kaggle: Global Weather Repository](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository)

---

## 🚧 Data Cleaning & Preprocessing:

- **Missing Values:**  
  Filled numerical missing values with median, categorical with mode.
- **Outliers:**  
  Outliers capped at the 1st and 99th percentiles.
- **Normalization:**  
  Numeric features normalized using StandardScaler.

---

## 🔎 Exploratory Data Analysis (EDA):

- Visualized trends in temperature and precipitation.
- Created correlation heatmap identifying key relationships among features.

---

## 📈 Forecasting Models:

- Built and evaluated **ARIMA** and **Exponential Smoothing** models.
- Developed an **Ensemble Forecasting model** by averaging ARIMA and Exponential Smoothing predictions.
- Evaluated models with metrics:
  - **Mean Squared Error (MSE)**
  - **Mean Absolute Error (MAE)**
  - **Root Mean Squared Error (RMSE)**

---

## 🔍 Advanced EDA (Anomaly Detection):

- Applied **Isolation Forest** to detect anomalies in weather data (temperature, humidity).

---

## 🎯 Unique Analyses:

- **Climate Analysis:** Long-term average temperatures across countries.
- **Environmental Impact:** Correlation between weather variables and air quality metrics.
- **Feature Importance:** Used Random Forest to find most influential features predicting temperature.
- **Spatial Analysis:** Visualized geographical patterns of temperature across regions.
- **Geographical Patterns:** Compared temperature distributions by country.

---

## 🎖️ Key Results & Insights:

- **Ensemble forecasting** produced the most accurate predictions.
- Humidity and precipitation significantly influenced temperature prediction.
- Identified significant geographical variations and regions prone to anomalies.

---

## 🛠️ Tools & Technologies Used:

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels)
- Jupyter Notebook

---

## ▶️ How to Run Locally:

### Step 1: Clone the repository
```bash
git clone https://github.com/your_username/Weather_Trend_Project.git
