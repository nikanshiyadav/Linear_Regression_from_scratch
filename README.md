# Linear_Regression_from_scratch
Code for calculating Linear Regression coefficients using gradient descent method, experimenting with different variables and parameters

The dataset contains information about energy consumption by appliances and different environment factors like temperature, humidity, weather etc. We must determine the relationship between the energy consumption and the given factors.
https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction

A linear regression model on the dataset was implemented to predict the energy usage of appliances., utilizing the gradient descent algorithm with batch update. Sum of squared error normalized by 2*number of samples [J(β0, β1) = (1/2m)[Σ(yᶺ(i) – y(i))2 ] was used as cost and error measures, where m is number of samples
