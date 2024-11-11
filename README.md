# ICICI Bank Stock Price Forecasting Project

This repository contains a comprehensive time series analysis and forecasting project focused on ICICI Bank stock prices. We utilize advanced statistical models, including **SARIMA** and **Holt-Winters Exponential Smoothing**, to analyze historical data, identify trends and seasonality, and build robust models for forecasting future stock prices.

## Project Structure

├── data/ │ └── icici_bank_stock_data.csv # Raw and processed stock price data ├── notebooks/ │ └── data_preprocessing.ipynb # Data cleaning and preprocessing │ └── exploratory_data_analysis.ipynb # EDA with plots and initial findings │ └── forecasting_models.ipynb # SARIMA and Holt-Winters model implementation ├── plots/ │ ├── stock_plot.png # Time series plot of ICICI Bank stock prices │ ├── acf_pacf_plots.png # ACF and PACF plots before and after differencing │ ├── seasonal_decomposition.png # Seasonal decomposition of the time series │ ├── sarima_forecast.png # SARIMA model forecast plot │ └── exp_smoothing_forecast.png # Holt-Winters forecast plot ├── README.md # Project overview and details ├── requirements.txt # List of dependencies └── report.pdf # Full project report with analysis and results
