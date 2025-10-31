🚀 Results Summary

Multiple gradient boosting algorithms were tested to predict EV charging energy consumption using session, site, and time-based features.

CatBoost achieved the best performance with an R² = 0.756, MAE = 5.61 kWh, and RMSE = 7.95 kWh on the test set.

The model accurately captures daily and station-level demand variations, providing valuable insight for operational planning and load forecasting of public EV infrastructure.

LightGBM and XGBoost achieved comparable results but required more preprocessing for categorical features.

Overall, the project demonstrates a robust end-to-end ML workflow for energy demand forecasting using real-world EV charging data.
