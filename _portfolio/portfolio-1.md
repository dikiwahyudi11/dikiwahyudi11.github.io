---
title: "Monthly Airline Passenger Forecasting Using SARIMA Analysis"
excerpt: "<br/><img src='https://miro.medium.com/v2/resize:fit:1400/0*4Rsuo3vPWquNYvjd'>"
collection: portfolio
---

![Time Series Analysis](https://miro.medium.com/v2/resize:fit:1400/0*4Rsuo3vPWquNYvjd) <br>
*Figure 1: Illustration of Time Series Analysis Method*

### Introduction
This project is conducted as part of the course "Time Series Analysis". This project aims to forecast the monthly airline passenger count of the United States from 1949 to 1960 (`AirPassengers`).

### Methods
Seasonal Autoregressive Integrated Moving Average (SARIMA) is an extension of the ARIMA model that incorporates seasonality. It is denoted as $`\text{SARIMA}(p, d, q)(P, D, Q)_m`$, where:
- $`p`$, $`d`$, and $`q`$ are the non-seasonal AR, differencing, and MA parameters, respectively;
- $`P`$, $`D`$, and $`Q`$ are the seasonal AR, differencing, and MA parameters, respectively;
- $m$ is the seasonal period.

### Key Findings
1. **Linear Model Suitability**: A linear model is deemed inadequate for modeling this dataset due to its inability to capture seasonal effects. The appropriate model for the data is found to be the natural logarithm of `AirPassengers`, represented by $`\text{ARIMA}(0, 1, 1)(0, 1, 1)_{12}`$, with the estimated model:
   
$$\ln(Y_t) - \ln(Y_{t - 1}) - [\ln(Y_{t - 12}) - \ln(Y_{t - 13})] = e_t -0.3424e_{t - 1} - 0.5405e_{t - 12} + 0.1850672e_{t - 13}.$$

3. **Residual Analysis**: The residuals of the model satisfy the diagnostic model assumptions, although visually, they may not closely resemble a normal distribution.

4. **Forecasting Performance**: Forecasting for the `test` data yields a MAPE value of 1.478059 < 10, indicating highly accurate forecasting. The original data and fitted values closely align on the time plot. For forecasting the next 4 years, starting from the forecast origin, which is the end of the `train` data, the forecast limit widens as time progresses. The forecasting values exhibit an increasing trend, suggesting a potential rise in monthly airline passenger numbers for US airlines in the future.

### Credit to Team Members
This project was a collaborative effort, and credit goes to the entire team for their contributions to data collection, analysis, and interpretation.

### Uploaded File Description
- `Project Model Peramalan_Kelompok B.Rmd`: R Markdown script for performing SARIMA analysis on the monthly airline passenger data.
- `Project Model Peramalan_Kelompok B.pdf`: Comprehensive report summarizing the findings and conclusions of the SARIMA analysis..

### GitHub Repository
The code and file for this project can be found [here](https://github.com/dikiwahyudi11/Monthly-Airline-Passenger-Forecasting). 
