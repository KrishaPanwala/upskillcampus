# upskillcampus
This project aims to develop a robust traffic forecasting system to support the transformation of various cities into smart cities. By analyzing and forecasting traffic patterns at key junctions, we can help the government improve the efficiency of urban transportation and infrastructure planning.

**Dataset**
The dataset used in this project contains traffic volume data collected at four key junctions in the city. The data includes the following columns:
DateTime: Timestamp of the data point.
Junction: Identifier for the junction.
Vehicles: Number of vehicles recorded at the junction.
Additional columns for preprocessing, such as day_of_week and hour_of_day.

**Methodology**
Data Preprocessing: Convert timestamps, extract features.
Modeling: Use SARIMAX for forecasting.
Evaluation: Cross-validation with MAE and RMSE metrics.

**Results**
The model provides forecasts for traffic volume at each junction.
Cross-validation results show the model's accuracy with MAE and RMSE metrics.
Visualizations of actual vs. forecasted traffic volume help interpret the model's performance.
