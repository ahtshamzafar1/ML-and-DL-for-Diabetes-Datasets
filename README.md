# Time Series Data Analysis
 
# Interactable plots 
The python notebook demonstrates a better visualization technique for on-the-go interation with the data, as compared to fixed non-moveable plots.
You can use pre-defined time frame buttons for quick zooming into particular parts of data. Along with these buttons the horizontal slider with zooming functionality can be used to narrow the search area as per application requirement. 

# Stationarity - Decomposition - Periodicity
The Notebook contains multiple attributes including following:
1. To check stationarity of the data using ADF and KPSS tests.
2. To decompose data into components (seasonal / trend / residual) to analyze variability in data.
3. Autocorrelation plots
4. Moving average plots
5. To Analyze if there exists some periodicity in data, and what interval the periodicity is valid. 

# ARIMA
The python note is a complete workflow for implementation of ARIMA Model. 
The Components of notebook include:
1. Import Data
2. Clean and convert data
3. Visualize data
4. Analyze data for different dataframe sizes (Stationarity - Seasonality - Periodicity)
5. Apply ARIMA on different data frames. Arima parameters are estimated using ACF and PACF graphs.
6. Estimate error metrics for original and predicted data. Mean Absolute Error (MAE) - Mean Squared Error (MSE)

# SVM - Support Vector Regressor
The python note is a complete workflow for modular implementation of SVR Model. It includes the following sections. 
1.  Import libraries
2.  Transform a time series dataset into a supervised learning dataset(This step includes converting a naive time series data into a supervised dataset. The number of values to be used as lag for supervised dataset is sent as a parameter to the function).
3.  Split a univariate dataset into train/test sets
4.  Fit an support vector regressor and make a one step prediction
5.  Walk-forward validation for univariate data
6.  load the dataset
7.  Transform the time series data into supervised learning
8.  Evaluate 
9.  Plot expected vs predicted

# Gradient Boost Regressor (XB Boost)
The python note is a complete workflow for modular implementation of XB Boost Model. It includes the following sections. 
1.  Import libraries
2.  Transform a time series dataset into a supervised learning dataset(This step includes converting a naive time series data into a supervised dataset. The number of values to be used as lag for supervised dataset is sent as a parameter to the function).
3.  Split a univariate dataset into train/test sets
4.  Fit an Gradient Boost Regressor and make a one step prediction
5.  Walk-forward validation for univariate data
6.  load the dataset
7.  Transform the time series data into supervised learning
8.  Evaluate 
9.  Plot expected vs predicted

# Random Forest Regressor
The python note is a complete workflow for modular implementation of Random forest regressor Model. It includes the following sections. 
1.  Import libraries
2.  Transform a time series dataset into a supervised learning dataset(This step includes converting a naive time series data into a supervised dataset. The number of values to be used as lag for supervised dataset is sent as a parameter to the function).
3.  Split a univariate dataset into train/test sets
4.  Fit a random forest regressor and make a one step prediction
5.  Walk-forward validation for univariate data
6.  load the dataset
7.  Transform the time series data into supervised learning
8.  Evaluate 
9.  Plot expected vs predicted

