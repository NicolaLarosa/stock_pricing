# stock_pricing
Download, manipulate and plot AXP ticker stock prices

Useful libraries:

1. datetime
2. matplotlib
3. mpl_finance
4. pandas
5. pandas_datareader

Goal:
Plot and analyze 4 years (from 2015 to 2019) of AXP stock prices (American Express Company).

Dataset columns:

Date 		       High        Low       Open      Close     Volume     Adj Close

2015-01-02  93.940002  92.139999  93.169998  93.019997  2437500.0   85.268341

Date			      datetime
High			      float64
Low             float64
Open            float64
Close           float64
Volume          float64
Adj Close       float64

Business meaning:

Date        calendar date
High	      max price in the day
Low	        min price in the day
Open	      value of the price when the exchange market opens
Close	      last value of the at the end of the day
Volume	    volume of stock exchanged at the end of the day
Adj Close	  is the closing price after adjustments for all applicable splits and dividend distributions


Steps:
- Grabbing AXP stock prices from yahoo with pandas_datareader
- Cleaning and manipulating data with pandas
- Plotting data using matplotlib and mpl_finance (candle stick)
