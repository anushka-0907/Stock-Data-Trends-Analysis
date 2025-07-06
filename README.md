# Stock-Data-Trends-Analysis

This project analyzes historical stock data to understand trends, visualize price movements, and evaluate performance. It uses time-series data to explore patterns and generate insights into a company's stock performance.

## Objective

To analyze stock price and revenue data for selected companies (Tesla and GameStop) and visualize key trends using Python and interactive plots.

## Data Sources

* **Stock Price Data**: Retrieved using the `yfinance` Python library.
* **Revenue Data**: Web-scraped from [MacroTrends.net](https://www.macrotrends.net/) using `requests` and `BeautifulSoup`.

## Key Steps

1. **Data Collection**

   * Downloaded historical stock prices using `yfinance`.
   * Scraped quarterly revenue data using `requests` and `BeautifulSoup`.

2. **Data Cleaning**

   * Removed missing values and converted date formats.
   * Aligned stock data and revenue timelines.

3. **Visualization**

   * Line plots for stock closing prices over time.
   * Dual-axis plots combining stock price and revenue trends.

4. **Custom Plot Function**

   * Created a reusable function `make_graph()` to display stock vs revenue trends using `plotly.graph_objects`.

## Tools & Libraries

* Python
* Pandas, NumPy
* yfinance
* BeautifulSoup, requests
* Plotly, Matplotlib
