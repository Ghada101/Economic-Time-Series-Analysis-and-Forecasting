# \# 📊 Time Series Forecasting Project
This project focuses on forecasting economic indicators using time series analysis techniques in R. Two datasets representing real-world economic trends were analyzed to uncover temporal patterns and predict future values using statistical modeling.

# \## 🔍 Project Objectives

- Understand the behavior of economic indicators over time

- Identify trends, seasonality, and patterns

- Build robust forecasting models using ARIMA

- Evaluate model performance using residual diagnostics and statistical tests 

# \## 📁 Datasets

# 1\. \*\*Dataset 1: MRTSSM4413USN\*\*  

- Source: FRED (Federal Reserve Economic Data)  

- Retail sales data for selected sectors in the U.S.

# 2\. \*\*Dataset 2: HOOVMN03JPM661N\*\*  

- Source: FRED  

- Housing and construction metrics in Japan

# \## 🛠️ Methods \& Workflow

- Data import and preprocessing using `fredr`

- Outlier removal and lag analysis

- Trend adjustment via linear and segmented regression

- ARIMA model selection with ACF/PACF and stationarity checks

- Residual diagnostics: Ljung-Box test, ACF of residuals

- Forecast generation and visualization using the `forecast` package

# \## 📈 Models Used

- \*\*Dataset 1\*\*: ARIMA(3,1,2) with drift  

- \*\*Dataset 2\*\*: ARIMA(1,0,5) with non-zero mean

# \## ✅ Results

Both models successfully captured underlying temporal dynamics and produced meaningful forecasts for future time points. The diagnostic checks confirmed the appropriateness of the selected models, and the visualizations helped interpret short-term and long-term trends.

# \## 📦 Tools \& Libraries

- R, RStudio

- `fredr`, `forecast`, `tseries`, `ggplot2`

# \## 📎 Notes

This project demonstrates end-to-end time series modeling and forecasting, with emphasis on model diagnostics and interpretation. It can be extended to other datasets or productionized for continuous monitoring.



