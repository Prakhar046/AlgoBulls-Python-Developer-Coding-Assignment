# AlgoBulls-Python-Developer-Coding-Assignment


# Algorithmic Trading Strategy

This repository contains code for a simple algorithmic trading strategy implemented in Python. The strategy fetches intraday data for US stocks using the Alpha Vantage API, computes a moving average indicator, generates trading signals based on the indicator, and plots a candlestick chart.

## Prerequisites

Before running the code, make sure you have the following prerequisites installed:

- Python 3.x
- Required Python packages (install using `pip`):
    - alpha_vantage
    - pandas
    - mplfinance

## Setup

1. Clone the repository:


2. Install the required Python packages:


## Configuration

To fetch intraday data from the Alpha Vantage API, you need to provide your API key. Follow these steps to configure your API key:

1. Sign up for a free Alpha Vantage account at https://www.alphavantage.co/.
2. Retrieve your API key from your account dashboard.
3. Open the `config.py` file in a text editor.
4. Replace the placeholder value for `API_KEY` with your actual Alpha Vantage API key.
5. Save and close the `config.py` file.

## Usage

To run the algorithmic trading strategy, follow these steps:

1. Open the Jupyter Notebook:


2. Navigate to the directory where you cloned the repository and open the `algorithmic_trading_strategy.ipynb` file.

3. Run each cell in the notebook sequentially to execute the code.

4. The notebook will fetch intraday data, compute the moving average indicator, generate trading signals, and plot a candlestick chart.

## Results

After executing the code, you will see the following results:

- The trading signals DataFrame will be displayed, showing the timestamps and corresponding signals ('BUY' or 'SELL').
- A candlestick chart will be generated, showing the intraday stock price and the moving average indicator.

Feel free to modify the code and experiment with different parameters to customize the strategy or analyze other stocks.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the code, please feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).


