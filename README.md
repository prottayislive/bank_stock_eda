# Project Report: Exploratory Data Analysis of Bank Stocks
[view code](https://github.com/prottayislive/bank_stock_eda/blob/main/us_bank_stocks_eda.ipynb)

### 1. Introduction

This project conducts an exploratory data analysis (EDA) on the stock prices of key banks from 2006 - 2023, focusing on Bank of America, Citigroup, Goldman Sachs, JPMorgan Chase, Morgan Stanley, and Wells Fargo. Utilizing Python's robust libraries—pandas, numpy, matplotlib, seaborn, and Plotly—we explore historical stock performance to decipher trends, particularly emphasizing the impact of the 2008 financial crisis and subsequent recovery phases, including the tumultuous period during the COVID-19 pandemic.

### 2. Data Acquisition

Data was obtained from Yahoo Finance via the `pandas_datareader` library, ensuring access to accurate and up-to-date financial data for our analysis. Our dataset covered the period from January 1st, 2006, to the current analysis cut-off in 2023, incorporating metrics such as **High, Low, Open, Close, Volume, and Adjusted Close** across six major banks.

### 3. Data Preparation

Separate data frames were designated for each bank based on their stock ticker symbols, later concatenated into a singular multi-level DataFrame `bank_stocks`. This structure facilitated analysis by allowing easy navigation through both banks and their respective stock information.

### 4. Exploratory Data Analysis

The analysis commenced by identifying the maximum closing price of each bank's stock throughout the study period, with Citigroup achieving the highest close.

#### 4.1 Standard Deviation and Risk Analysis

We assessed volatility and risk via standard deviation, with a specific focus on the 2020-2021 period, coinciding with the COVID-19 pandemic. This analysis revealed Citigroup and Wells Fargo as the most volatile, hence riskier investments during this timeframe, whereas Goldman Sachs and JPMorgan Chase showed the least volatility, indicating more stability amidst market upheavals.

#### 4.2 Pearson Correlation Matrix

The linear relationships between the stocks were examined using the Pearson correlation coefficient. Heatmaps and cluster maps of these coefficients elucidated how the stocks' movements were interrelated, shedding light on their co-movements or divergences.

### 5. Financial Charts

Advanced financial charts were created using Plotly and Cufflinks to visualize the data comprehensively. These included line plots for closing prices, histograms of returns, moving averages, candlestick charts, Bollinger Bands, and OHLC charts, providing deeper insights into the banks' stock price actions and market trends.

#### 5.1 Returns Histogram

Histograms for the distribution of returns for each bank, particularly from 2018 to 2023, helped understand recent performance and market sentiment.

#### 5.2 Moving Averages

The analysis of moving averages, especially for the year 2008 and the COVID-19 pandemic period, offered perspectives on market reactions to significant global events. Bank of America's 30-day moving average during these times highlighted the fluctuating market conditions.

#### 5.3-5.7 Advanced Charting

Further explorations included **simple moving averages, candlestick charts, Bollinger Bands, facet plots, and OHLC charts**. These advanced visualizations offered intricate details on stock price movements, volatility, and the banks' financial health over time.

### 6. Conclusions

Our exploratory analysis from 2006 - 2023 has provided valuable insights into the stock performance and market behavior of some of the largest US banks. The financial crisis of 2008 and the COVID-19 pandemic emerged as significant events influencing stock prices, with varying degrees of impact and recovery among the banks. This study highlighted Citigroup and Wells Fargo as the riskier stocks during the pandemic, offering a stark contrast to the stability exhibited by Goldman Sachs and JPMorgan Chase.

This project underscores the efficacy of Python and its data analysis libraries in dissecting financial market dynamics, serving as a crucial tool for investors, financial analysts, and enthusiasts interested in the intricacies of the stock market and banking sector performances.
