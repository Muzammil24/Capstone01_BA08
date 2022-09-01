# Capstone01_BA08

The repository contains the following:

1. Code for Topic Modelling (P_Topic_Modelling_DD_Aug.ipynb)
2. Time Series code using Fb_prophet (Time_Seriesv4_FB_Parameter_Tuned.ipynb)
3. Is the deplyment code for time series (01_Deployment_Code.zip)

01_Deployment_Code.zip uses flask to deploy the code that forecasts future values.


The same code( Time Series code using Fb_prophet (Time_Seriesv4_FB_Parameter_Tuned.ipynb)) is converted into a flask app to create and User interface to upload a file and forecast future values.

The UI asks for the following Information.

•	Date Column Name: Has to match exactly as mentioned in the CSV or Excel File

•	Feature/Variable to Forecast: Has to match exactly as mentioned in the CSV or Excel File 

•	Forecasting: The period to forecast for as a unit from available options (Daily, Weekly Monthly, Yearly)

•	Intervals you want to forecast.

