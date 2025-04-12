# FE5213 CPI Forecasting
This project focuses on the modelling of differenced inflation rates (based on CPI) in the US and UK economies. We found that AR and ADL models work better than non-traditional models such as Ridge and LSTM models.

The details of the relevant files are as described below:

|File Name | Description |
| -------- | ----------- |
|US_consolidated_df.csv|US Data File|
|UK_consolidated_df.csv|UK Data File|
|Consolidated_plots_US_UK_plot.ipynb|Code to generate EDA plots|
|data_combination.ipynb|Code to form dataframe for US and UK|
|data_cleaning.ipynb|Code for data cleaning|
|Preprocess_EDA_Project_2_US_Code.ipynb|Preprocessing code for US dataframe|
|Preprocess_EDA_Project_2_UK_Code.ipynb|Preprocessing code for UK dataframe|
|models_time_series_monthly.ipynb|Code for traditional models (Monthly analysis)|
|models_time_series_quarterly.ipynb|Code for traditional models (Quarterly analysis)|
|models_nontraditional.ipynb|Code for non-traditional models (Monthly and Quarterly analysis)|
|forecast_combination.ipynb|Code for forecast combinations|
