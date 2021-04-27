# Stock_Market_forecasting
# Forecasting Stock Market Prices

A time series is simply a series of data points ordered in time. In a time series, time is often the independent variable and the goal is usually to make a forecast for the future. Our Aim  is to create a model that can forecast the future stock price based on the model training and provided dataset.

### Data
We will be using a [Huge stock market dataset]from the Kaggle platform which has a very good collection of datasets.The file we will be using is present in following directory in the dataset zip file input\Data\Stocks\gs.us.txt
  
The data is presented in CSV format as follows : Date, Open, High, Low, Close, Volume, OpenInt.

Features:
  - Date
  - Open
  - High
  - Low
  - Close
  - Volume
  - OpenInt
  
Note that prices have been adjusted for dividends and splits.

### LICENSE OF DATASET : [LICENSE](https://creativecommons.org/publicdomain/zero/1.0/)

### Libraries Involved:

1. NumPy
2. Pandas
3. matplotlib
4. scikit-learn
5. statsmodels


### Steps :
1. Importing Libraries
2. Exploring the Dataset
3. Exploratory Data Analysis
> * Univariate Analysis
4. Data Preprocessing
5. Model Building
> * AUTOREGRESSIVE MODEL
> * MOVING AVERAGE MODEL
6. Evaluation
> * MEAN SQUARE ERROR
> * MEAN ABSOLUTE ERROR
> * ROOT MEAN SQUARE ERROR

## Models Used:
1. Autogregressive Model
2. Moving Average model
