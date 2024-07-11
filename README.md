# Air Quality Analysis and Prediction Model
## COVID-19's Impact on PM2.5 Concentrations and Climate Change: A Machine Learning Approach

## Overview

This repository contains a machine learning model developed using Python to analyze the impact of COVID-19 on PM2.5 concentrations and climate change. The model utilizes time series analysis to predict PM2.5 concentrations and explores the potential of machine learning in addressing climate change.

## Background

The COVID-19 pandemic has inadvertently provided a unique opportunity to reassess our priorities and strive for a more environmentally conscious future. This project aims to investigate the impact of COVID-19 on PM2.5 concentrations in India and explore the role of machine learning in climate change mitigation.

## Methodology

* Time series analysis was used to analyze the PM2.5 concentration data in India during the COVID-19 pandemic.
* SARIMA and Holt-Winters machine learning models were developed using Python to predict PM2.5 concentrations based on historical data.
* The Holt-Winters Model was concluded to be the better predictor as the SARIMA model failed to take into consideration the unexpected increase in PM2.5 concentrations.

## Key Findings

* The analysis revealed a significant decrease in PM2.5 concentrations in India during the COVID-19 pandemic.
* The machine learning model demonstrated the potential to predict PM2.5 concentrations with high accuracy.
* The project highlights the importance of sustained efforts to reduce emissions and transition towards a more sustainable future.
* The COVID-19 Lockdown impact on climate change and air quality can be expressed clearly based on the analysis in the project.
* The upliftment of lockdown in 2022 can also be seen to have had an exponential impact on the PM2.5 concentration, indicating poor air quality and higher climate change.

## Machine Learning Model

* The machine learning model was developed using Python and utilizes time series analysis to predict PM2.5 concentrations.
* The model can be used to forecast PM2.5 concentrations and support data-driven decision making for climate change mitigation.

## Future Directions

* The integration of machine learning into climate change research and policy can enhance our ability to adapt to and mitigate the impacts of climate change.
* The model can be improved by incorporating additional data sources and features to increase its accuracy and robustness.

## Repository Structure

* `df`: Contains the hourly dataset used for training and testing the machine learning model.
* `df_daily`: Contains daily transformed values for the same dataset.
* `df_month`: Contains monthly transformed values for the same dataset.
* `sarima_future_model`: Contains the Python code for the SARIMA machine learning model for future predictions.
* `forecast_model`: Contains the Python code for the Holt-Winters machine learning model for future predictions.
* `df_forecasted`: Contains the given and SARIMA Model forecasted monthly PM2.5 values.
* `df_holt_forecast`: Contains the given and Holt-Winters Model forecasted monthly PM2.5 values.

## References and Datasets

Dataset Source Link : https://www.kaggle.com/datasets/fedesoriano/air-quality-data-in-india
