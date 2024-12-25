# Portfolio Allocation_Part1
The file sp500_2022.csv contains daily returns for the (CRSP) S&P500 value-weighted
index with dividends (column vwretd) from 1/3/1972 through 12/31/2021. Download
the daily U.S. Treasury yield curve from here. That file has the daily parameters for the
Nelson-Siegel-Svensson yield curve model discussed in class. With those parameters,
you can calculate a zero-coupon bond yield for any maturity.   

(a) For the (CRSP) S&P500 with dividends, what was the average arithmetic and
geometric historical mean rate of return for daily returns, for monthly returns, for
annual returns from 1/3/1972 through 12/31/2021, and for 5-year returns from
1/3/1972 through 12/30/2016? Make sure to annualize the returns you report.

(b) Do the same for excess rates of return over zero-coupon bonds. You should choose
the maturity of the bonds to match the horizon of the returns so that the bond
returns are risk-free (i.e. known at the begining of each period). For example,
one-month S&P 500 returns should be compared to the returns of a one-month
zero-coupon bonds maturing at the end of each period. Again, make sure to
annualize the returns you report.
Note: Because the bond market is open fewer days than the stock market, there
are dates when data is missing. dropna() can be helpful to delete the dates when
either stocks or bonds are missing.

(c) Assume that the your coefficient of risk aversion, A, is equal to 4. How will you
allocate your capital between bonds and the index? HINT: Arithmetic returns
are more appropriate than geometric returns for this question.
