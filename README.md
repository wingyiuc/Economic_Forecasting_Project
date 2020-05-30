# Economic Forecasting Project
A typical global equity market index portfolio consists of different stocks for risk diversification. As Moody’s recently lowered Hong Kong’s rating from Aa2(negative) to Aa3(stable), it is possible that there existed capital flow from Hong Kong to New Zealand which is rated Aaa(stable) for hedging purpose. Thus, it is believed that the two time-series share common information about the macro economic conditions, nonsynchronous trading is applicable. In the following analysis, rolling prediction is used as the Covid-19 pandemic induced change in data structure and 1-year sample is used for prediction.
## Getting Started
The following instructions will get you a replication of the project results.
### Prerequisites
Required R packages are: `data.table`, `readxl`, `stringr`, `dplyr`, `forecast`, `ggplot2`, `tseries`, `stats`, `psych`, `fUnitRoots`, `lmtest`, `pastecs`, `FitAR`, `aTSA`, `itsmr`, `pracma`, `arfima`, `dse`, `smooth`, `fGarch`.
## Stock 1 - HSI (Hong Kong)
The HSI is a highly active market with a 1,748,940,800 average volume over the past month. By the Efficient Market Hypothesis (EMH), it is believed that the time series process of HSI would be white noise and we could not forecast the future returns based on historical data.
The notebook `Economic Forecasting Project (Hong Kong)` contains 3 sections: **data exploration**, **model selection** and **model predictions**. 
## Stock 2 - NZ50 (New Zealand)
Contrasting to HSI, NZ50 is only having a 49,914,886 30 day average volume. It is believed that it is a less efficient market, thus may show more autocorrelation in data.
The notebook `Economic Forecasting Project (New Zealand)` contains 3 sections: **data exploration**, **model selection** and **model predictions**. 
## Equally Weighted Portfolio
An equally weighted portfolio is formed with HSI and NZ50, and we can see if there exists any commonly shared information between the two stocks, such that we can do nonsynchronous trading.
The notebook `Economic Forecasting Project (Portfolio)` contains 3 sections: **data exploration**, **model selection** and **model predictions**. 
