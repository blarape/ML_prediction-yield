# ML_prediction-yield
3-months yield


This project aims to predict the short-term (3-month) performance of top 100 US companies using machine learning. The approach combines data from **SimFin** and includes:


i) Balance sheet

ii) Income statement

iii) Cash flow statement


I have added other metrics like volatility and moving averages using **Yahoo Finance** (straight from python library **yfinance**)
The target has been calculated using data downloaded from **yfinance** as well.


<src/data_sample> includes 4 csv files. 3 of them are raw data from **SimFin**. The remaining file <df_filtered> is the merged and filtered data and can be used as sample.


I have tried merging more and less features and used two different models for preditions but came to the conclusion that the data is not sufficient to begin with. I had a strong feeling that there could be some possibility for prediction with financial data but either is not sufficient data itself or there is macronoeconomic and sentiment data missing as well --or my data analysis is wrong all along, since there is no correlation either--. I'm happy to get feedback as I would like to continue with this project in the future.


The conclusion for this project is not good at all but I have been learning all the way. :) 
