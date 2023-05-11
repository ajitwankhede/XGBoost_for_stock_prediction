# XGBoost_for_stock_prediction
 XGBoost for stock trend & prices prediction

#### About Dataset

High-quality financial data is expensive to acquire and is therefore rarely shared for free.
Here I provide the full historical daily price and volume data for all US-based stocks and ETFs trading on the NYSE, NASDAQ, and NYSE MKT. 
It's one of the best datasets of its kind you can obtain.

The data (last updated 11/10/2017) is presented in CSV format as follows: Date, Open, High, Low, Close, Volume, OpenInt. 
Note that prices have been adjusted for dividends and splits.

Data base available here (https://www.kaggle.com/datasets/borismarjanovic/price-volume-data-for-all-us-stocks-etfs)

#### Introduction
In this repo I use XGBRegressor from XGBoost library to predict future prices of stocks using technical indicator as features.
