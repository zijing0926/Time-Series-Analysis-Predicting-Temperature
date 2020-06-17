# Time-Series-Analysis-Predicting-Temperature
This project uses two models to predict the temperature using time series technique. It starts with building a group-by estimator that takes an estimator factory. The estimator factory is a collection of estimators for each city. In this case, each city's estimator is only fitting into its own data and make corresponding predictions. The first model simply uses the random forest models to predict each city's temperature. Another model used is a Fourier model that captures the seasonal features. Using month and hour, the group estimator is making better predictions for each city.

Skills: 
Time Series Analysis, Customized Model, Group Estimator, Estimator Factory, Fourier Model, Random Forest
