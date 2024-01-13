# Stock Analysis Using YFinance

## About

In this project, I conducted a comprehensive analysis of the stocks of four prominent companies - Amazon, Google, Apple, and Microsoft - spanning the last 2 years. The analysis covered various aspects, including changes in stock prices, stock volume, moving averages, daily return averages, trend creation, and correlation between daily returns.

## Python Libraries

- **pandas**: Used for data manipulation and analysis.
- **numpy**: Essential for numerical operations, providing support for mathematical functions and operations on arrays.
- **yfinance**: This library enables easy access to financial data from Yahoo Finance. It simplifies the process of fetching stock-related information.
- **matplotlib**: A versatile plotting library, useful for creating static, interactive, and animated visualizations in Python.
- **plotly express**: Ideal for creating interactive visualizations. It adds a layer of interactivity to your plots, enhancing the user's ability to explore data.
- **seaborn**: Built on top of matplotlib, seaborn is used for creating aesthetically pleasing statistical graphics. It simplifies the process of creating informative and attractive visualizations.
- **datetime**: Facilitates working with dates and times.

### Data Collection and Cleaning

- The data for this analysis was directly collected using the YFinance API, which was installed via pip. The start date was set to two years prior to the end date.
```python
#start and end date
start_date = datetime(end.year-2,end.month,end.day-1)
end_date = datetime(end.year,end.month,end.day-1)
```
- Stock data for the companies (Apple, Amazon, Google, and Microsoft) was downloaded directly from YFinance as DataFrames using their respective tickers (identifiers).
```python
#download stock data for 2 years for Apple,Amazon,Google and Microsoft
import yfinance as yf
tick1 = 'AMZN'
tick2 = 'AAPL'
tick3 = 'GOOG'
tick4 = 'MSFT'
AMZN = yf.download(tick1,start_date,end_date)
AAPL = yf.download(tick2,start_date,end_date)
GOOG = yf.download(tick3,start_date,end_date)
MSFT = yf.download(tick4,start_date,end_date)
```
- The collected data was clean, and no additional data cleaning steps were required.

### Visualization Details

- I utilized matplotlib.pyplot (plt.plot) for visualizing the changes in stock prices, volumes and moving averages with a window size of 5 for the selected companies.
- For visualizing the frequency of daily return trends, I employed a pie chart using px.pie.
- The correlation between daily returns was represented using a heatmap with seaborn.

## Conclusion

After analyzing data from January 12, 2022, to January 12, 2024, Microsoft emerges as a well-balanced performer among the four companies. Despite exhibiting a high negative daily return trend, Microsoft maintains equilibrium across low, moderate, and high trends, showcasing resilience in the stock market. Notably, Microsoft demonstrates a strong correlation with Google and Apple, making them potentially lucrative investment choices, given Microsoft's stability.

