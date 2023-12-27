# House Price Prediction

Agenda: Model for prediction on HPI(House Price Index)in US using some key supply-demand factors

'Datasets Collected' folder: This folder contains all the datasets I collected online form the reference link on the factor that affects HPI over last 20 years. 
It also contains .pynb file that demonstrates how I used that data sets to prepare Analytics Base Table that is used further in my model.

'Analytics_Base_Table.csv': This is the base table I generated out of the datasets I collected

'Assignment US_HPI_Prediction Key_Supply-Demand_Factors.ipynb': This jupyter notebook worksheet demonstrates how I had built the model using the base table.
And it shows the steps I followed to built model like Data Preprocessing, Missing values imputation, EDA, Applying Linear Regression, Cross Validation on accuracy scores,
knowing the best model out of LinearRegression, svm.SVR, Ridge, Lasso and DecisionTreeRegressor with the best parameters tuning.
Also it demonstrates the application of the best model with best parameters for predicting HPI on a given random values of the key factors. 
