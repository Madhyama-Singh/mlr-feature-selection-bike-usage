# Multiple Linear Regression with Feature Selection on Bike Sharing Data 🚲📊

This project performs statistical inference and feature selection techniques on a multiple linear regression (MLR) model using a dataset of daily bike rental counts. It explores **forward selection**, **backward elimination**, and **stepwise selection**, with evaluation based on the Akaike Information Criterion (AIC).

---

## 📌 Objective

- Use MLR to predict the daily count of bike rentals (`cnt`) based on weather, seasonality, and other contextual features.
- Select optimal features using statistical methods and compare models.
- Interpret model summaries using statistical metrics (p-values, R², AIC).
- Visualize data for insights.

---

## 🧾 Dataset

- The dataset `day[1].csv` (used via local path) contains:
  - `cnt`: Total rental bikes count (target)
  - Independent variables include:
    - Categorical: `season`, `weathersit`, `weekday`, `holiday`, `workingday`
    - Continuous: `temp`, `atemp`, `hum`, `windspeed`

---

## 🧠 Concepts Covered

- **Dummy variable encoding** for categorical data
- **Forward Selection**, **Backward Elimination**, and **Stepwise Selection**
- **AIC-based model selection**
- **OLS Regression Analysis** using `statsmodels`
- **Visualizations**: Actual v/s Predicted values

---

## 🔍 Methodology

### 🛠️ Feature Selection Techniques:

- **Forward Selection**: Starts with no features, adds one at a time based on best AIC.
- **Backward Elimination**: Starts with all features, removes one at a time based on worst AIC.
- **Stepwise Selection**: Combination of forward and backward with both add/remove steps.

---




