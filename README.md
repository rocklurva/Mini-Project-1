# Mini-Project-1
------------------
## Group Members : Jonathan Martinez, Cindy Wong, Mylene Marsden, Christian Torres

------------------
### Objective
Looking at the historical stock price, returns, and other relevant information of the S&P500 stock market index:

* Analyse the S&P500 stock price performance from Jan 2003 to Jan 2023, then compare to today's price and run a trenline/regression model to predict price of the stock in 5 years from now.
* Identify years of positive and negative return of the S&P500 from Jan 2003 to Jan 2023.
* Analyse the performance of the S&P500 economic sectors in periods of crisis (negative returns) from Jan 2003 to Jan 2023. Then, research what happened in those negative years and identify whether the affected sectors could recover after the crisis.
* Explore the trends/performance of each sector for the last 5 years and identify Top 3 outperfroming sector and Top 3 underperforming sectors.
* Identify the current weight of each sector on the S&P500, based on market capitalisation.

-------------------
### Audience
Our target audience is someone who is looking to invest in the stock market and would like to reduce the risk by having some insights about the behaviour of the economic sectors based on the S&P500. 

-------------------
### Timeframe and figures
Historical and current data of the S&P500 Index, such as price, returns, sectors, market capitalisation. From January 2003 to January 2023.

-------------------
### Understanding S&P500
The S&P 500 Index, or Standard & Poor's 500 Index, is a market-capitalization-weighted index of 500 leading publicly traded companies in the U.S. It covers approximately 80% of available marker capitalisation. In other words, S&P500 tracks the stock performance of 500 large companies listed on stock exchanges in the United States and it is one of the most commonly followed equity indices.

-------------------
### Content
1. What is the S&P500 and why it is important in the US stock market. 
2. Trend of the S&P500 average stock price from 2003 to 2023. Current price and prediction.  **Graph: Line plot** & **Regression Model**
3. Years of positive (green) and negative (red) return of the S&P500. **Graph: Bar chart**.
4. Stock price of the economic sectors in periods of negative return. Compare year prior the crisis, year of the crisis, year after the crisis. **Graph: Horizontal Bars grouped by sector comparing the 3 years. **
5. Trend of the average stock price of each S&P500 economic sector per year. **Graph: Line plot**.
6. Performance of the secotrs based on percentage of return in the last 5 years (2018 - 2020). **Graph: Pie Chart OR Line Plot**. Identify Top 3 outperforming sectors and Top 3 underperforming sectors.
7. Current percentage of participation by weitgh of each sector in the S&P500 index (sector breakdown based on market capitalisation). **Graph: Pie Chart**.

-------------------
### Main Resources
1. Info about S&P500: https://www.spglobal.com/spdji/en/indices/equity/sp-500/#overview
2. API to get stock price per symbol quotes: https://site.financialmodelingprep.com/developer/docs/stock-api/#Python
3. API to get stock price per index (S&P500): https://twelvedata.com/
4. Historical data.
4.1 S&P 500 Index Historical Data:
•	S&P 500 (SPX): https://au.investing.com/indices/us-spx-500-historical-data
4.2. S&P 500 Sectors Historical Data:
•	S&P 500 Information Technology (SPLRCT): https://au.investing.com/indices/s-p-500-information-technology-historical-data
•	S&P 500 Health Care (SPXHC): https://au.investing.com/indices/s-p-500-health-care-historical-data
•	S&P 500 Consumer Discretionary (SPLRCD): https://au.investing.com/indices/s-p-500-industrials-historical-data
•	S&P 500 Industrials (SPLRCI): https://au.investing.com/indices/s-p-500-industrials-historical-data
•	S&P 500 Consumer Staples (SPLRCS): https://au.investing.com/indices/s-p-500-consumer-staples-historical-data
•	S&P 500 Energy (SPNY): https://au.investing.com/indices/s-p-500-energy-historical-data
•	S&P 500 Financials (SPSY): https://au.investing.com/indices/s-p-500-financial-historical-data
•	S&P 500 Materials (SPLRCM): https://au.investing.com/indices/s-p-500-materials-historical-data
•	S&P 500 Utilities (SPLRCU): https://au.investing.com/indices/s-p-500-utilities-historical-data
•	S&P 500 Real Estate (SPLRCREC): https://au.investing.com/indices/s-p-500-real-estate-historical-data
•	S&P 500 Telecom Services (SPLRCL): https://au.investing.com/indices/s-p-500-telecom-services-historical-data
5.Explanation about each sector of the S&P 500: https://corporatefinanceinstitute.com/resources/valuation/the-sp-sectors/
6. List of S&P500 Constituents/Companies: https://www.kaggle.com/datasets/alexanderxela/sp-500-companies

-------------------
### Some examples for the visualisations
1. For the 2 point of the content: https://www.google.com/finance/quote/.INX:INDEXSP?sa=X&ved=2ahUKEwjj8ILZnO38AhV86jgGHRs9BM4Q3ecFegQINhAg&window=MAX
2. For the 3 point of the content: https://www.macrotrends.net/2526/sp-500-historical-annual-returns
3. For the 4 point of the content: https://www.businessinsider.com/stock-market-news-rotation-has-flipped-it-completely-upside-down-2017-9
4. For the 5 point of the content: https://www.stlouisfed.org/on-the-economy/2021/march/covid19-impacted-stock-performance-industry
5. For the 6 point of the content: https://advisor.visualcapitalist.com/sp-performance-in-2020-by-sector/  OR https://www.spglobal.com/spdji/en/index-family/equity/us-equity/sp-sectors/#overview
6. For the 7 point of the content: https://www.spglobal.com/spdji/en/indices/equity/sp-500/#data

-------------------
### Other Resources 
* https://www.kaggle.com/datasets/andrewmvd/sp-500-stocks?select=sp500_companies.csv
* https://www.kaggle.com/datasets/andrewmvd/sp-500-stocks?select=sp500_index.csv
* https://www.kaggle.com/datasets/andrewmvd/sp-500-stocks?select=sp500_stocks.csv
* https://www.kaggle.com/datasets/guillemservera/sp500-nasdaq-spy-qqq-ohlcv-data?select=SP500.csv
* https://www.kaggle.com/datasets/guillemservera/sp500-nasdaq-spy-qqq-ohlcv-data?select=NASDAQ_100.csv
* https://www.kaggle.com/datasets/guillemservera/sp500-nasdaq-spy-qqq-ohlcv-data?select=SP500.csv
* https://www.slickcharts.com/sp500
* https://www.kaggle.com/datasets/paultimothymooney/stock-market-data
* https://www.kaggle.com/datasets/alexanderxela/sp-500-companies
* https://www.spglobal.com/spdji/en/indices/equity/sp-500/#data

-------------------
### Team Meetings
|Meeting Dates | Meeting Time | Task List | Task Distribution |
|--|--|--|--|
|23 Jan, Mon| 1830 | Source Dataset & Discuss the dataset | - |
|24 Jan, Tues | 2030 | Discuss the dataset/ information that we'll extract from the dataset/ use for our analysis | - |
|25 Jan, Weds | 1900 | Finalise the Methodology and measure that we'll be using & distribute tasks amongst 4 member| - |
|26 Jan, Thurs | - | - | - |
|27 Jan, Fri to 29 Jan, Sun | Discuss among ourself | Data Cleaning and Merging Datasets | Jonathan |
|30 Jan, Mon to 31 Jan, Tues | Discuss among ourself | Start Visualisation | ALL |
|01 Feb, Weds | TBC | Analyse Data (Group) / write up Discussion and Summary, Create PPT | ALL |
|02 Feb, Thurs | 1830 | Presentation Day | ALL |

-------------------
### Task Distribution
- Data Clean and Merge Datasets // Jonathan
- Data Visualisation // all
- Analysis of the data // all
- Report Writing // all
- Create powerpoint / slide preparation / Script writing // all
