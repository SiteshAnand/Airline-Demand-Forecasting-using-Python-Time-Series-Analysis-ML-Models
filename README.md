#Airline-Sales-Forecasting-using-Python-Time-Series-Analysis-ML-Models

#Enviornment - Anaconda-Web Jupyter Notebook

#Database used - AirPassenger.csv

#Approach:Conducted EDA with trend analysis, distribution (histogram), and boxplotsPerformed,

time-series decomposition (Trend + Seasonality + Residual) with period=12 to isolate patternsApplied log transformation to convert 

multiplicative seasonality to additive and stabilize varianceSplit data into Train (1949-56) and Test (1957-60) to validate on unseen

futureBuilt and compared 4 models: Linear Regression, Simple Average, 12-Month Moving Average, and Triple Exponential Smoothing (Holt-Winters)

Results:Identified clear exponential growth: 1,520k (1949) to 5,714k (1960) = 276% 

growthDetected strong seasonality: Peak Jul-Aug avg 351k vs Low Nov 232k (50% swing)Best model: Triple Exponential Smoothing with RMSE 29.67, outperforming 

Linear Regression (71.5), Moving Average (115.88), and Simple Average (213.45) by 58-88%

Business Impact: Proposed seasonal pricing strategy (premium Jun-Sep, discounts Nov-Feb), maintenance scheduling in low season, and adopting Holt-Winters for automated demand forecasting.

Skills: Python, Pandas, Matplotlib, Time Series Forecasting, Seasonal Decomposition, Holt-Winters, RMSE, Business Intelligence
