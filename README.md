# Five-Year-Historical-Performance-of-FTSE100-and-Bitcoin-Prices-in-GBP
A Take home assignment for Data Analyst role at AXA


## Financial Analysis Using Python and Pandas

This repository contains Python scripts for fetching, cleaning, analyzing, and visualizing historical data of FTSE100 (UK stock market index) and Bitcoin prices in GBP using the `yfinance` library and `pandas` for data manipulation.

### Scripts Overview

**`financial_analysis.py`**: Python script that fetches historical data of FTSE100 and Bitcoin prices from Yahoo Finance, cleans the data, calculates moving averages, daily returns, and performs analysis including summary statistics, correlation analysis, trend analysis, and volatility analysis.

### Requirements

The following Python libraries installed:

- `yfinance`
- `pandas`
- `matplotlib`
- `seaborn`

These libraries can be installed using pip:
pip install yfinance pandas matplotlib seaborn

### Usage


3. The script will fetch historical data for FTSE100 and Bitcoin in GBP for the past five years, perform data cleaning and analysis, and save the merged data to `merged_data.csv`.

4. Open the generated CSV file (`merged_data.csv`) in your preferred spreadsheet software or use it for further analysis.

### Files Included

- **`financial_analysis.py`**: Main script for data fetching, cleaning, analysis, and CSV export.
- **`merged_data.csv`**: CSV file containing cleaned and merged data of FTSE100 and Bitcoin prices with calculated metrics.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Data fetched using `yfinance`.
- Analysis and visualization performed using `pandas`, `matplotlib`, and `seaborn`.
