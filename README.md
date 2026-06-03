# Financial Market Explorer
This is a Python data analysis project which aims to fetch live stock price data using the yfinance library. The aim of this project was to build an algorithm which could calculate the stock returns, sort the returns from highest to lowest and display this data on a bar chart for visibility.

As well as this, I developed it further by adding calculations for volatility and Sharpe ratio and displaying this on a bar chart too. The volatility measures the unpredictability of the stocks daily returns over the 251 trading days in 2024, measured in standard deviation. The Sharpe ratio is the measure of the return per unit of risk.

## Technologies used
For this project I used Python, Pandas, Matplotlib, yfinance and .ipynb notebooks.

## Motivation
I was inspired to make this project by my interest in how finance can be integrated
within technology. Through building this project I aimed to develop my Python skills whilst gaining practical exposure to key financial concepts, such as risk-adjusted performance, highlighting the bridge between software development and the financial industry.

## Features
- Retrieves live data using yfinance library
- Calculates percentage return for each stock
- Ranks the stocks from highest to lowest return
- Visualises this rank using a bar chart.
- Calculates daily returns, annual volatility and Sharpe ratio
- Sorts Sharpe ratios into a dataframe from highest to lowest and displays this data on a bar chart.


## How to run?
1. Clone the repository
2. Create a virtual environment: 'python -m venv venv'
3. Activate it: 'source venv/bin/activate'
4. Install its dependencies: 'pip install pandas yfinance matplotlib'
5. Open the notebook in the 'notebooks\' folder and run all cells.

## Project Structure

financial-market-explorer/
|
|-- notebooks/
  |-- market_analysis.ipynb
|-- README.md
