# Solar Energy Generation Forecasting Using ARIMA and SARIMA

##  Project Overview

This project focuses on analyzing and forecasting solar energy generation using time series forecasting techniques in Python.

The dataset contains hourly solar energy generation data along with electricity load information. The main objective of this project is to understand historical solar generation patterns, identify daily seasonality, evaluate time series models, and forecast future solar energy generation.

The project applies statistical forecasting techniques including ARIMA and SARIMA and compares their forecasting performance using MAE and RMSE.

---

##  Project Objectives

The main objectives of this project are:

- Analyze hourly solar energy generation data.
- Convert and process timestamp data.
- Identify trends and seasonal patterns.
- Determine the frequency of the time series.
- Analyze daily seasonality in solar generation.
- Test the stationarity of the time series using the Augmented Dickey-Fuller (ADF) test.
- Split the dataset into training and testing periods.
- Build an ARIMA forecasting model.
- Build a SARIMA forecasting model.
- Compare model performance using MAE and RMSE.
- Select the better-performing forecasting model.
- Generate future solar energy forecasts.

---

##  Dataset

The dataset contains hourly observations of:

- `utc_timestamp` — Timestamp of the observation.
- `IT_load_new` — Electricity load.
- `IT_solar_generation` — Solar energy generation.

The dataset contains **8,784 hourly observations**.

The timestamp was converted into a proper datetime format and used as the time-series index.

---

##  Technologies and Libraries

The project was developed using Python.

### Tools

- Python
- Jupyter Notebook
- GitHub

### Python Libraries

- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Scikit-learn

---

##  Exploratory Time Series Analysis

The first step was to visualize solar energy generation over time.

The analysis showed that solar generation follows a clear daily pattern.

Solar generation:

- Is almost zero during nighttime.
- Starts increasing in the morning.
- Reaches higher levels during daylight hours.
- Gradually decreases in the afternoon.
- Returns to near-zero levels during the evening and night.

This indicates a strong **daily seasonal pattern**.


Since the data is recorded hourly, the daily seasonal period was identified as:

```text

24 hours


**Author**
**Uroosa khan**
