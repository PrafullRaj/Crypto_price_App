
# Crypto Web App

This is a cryptocurrency dashboard built using Streamlit, designed to retrieve and display cryptocurrency prices and other related information from **CoinMarketCap**. The app provides various visualizations, including price change charts, market cap charts, and market share pie charts.

## Features
- Retrieves live cryptocurrency data from [CoinMarketCap](https://coinmarketcap.com).
- Display selected cryptocurrency prices in either USD or BTC.
- Horizontal bar charts to show the percentage change of cryptocurrencies for different timeframes (1 hour, 24 hours, or 7 days).
- Market Cap bar charts for selected cryptocurrencies.
- Market share pie chart for Bitcoin, Ethereum, and other altcoins.
- Downloadable CSV file of the selected cryptocurrency data.
- Interactive data tables displaying prices and percentage changes of the selected cryptocurrencies.

## Deployment

This app is deployed using **Render**. You can access the live app at:

**[Live App Link](<[insert-your-app-link-here](https://crypto-price-app-90q4.onrender.com)>)**

## Setup and Installation

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Install the dependencies:**

   Make sure you have Python installed. Then run:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app:**

   Start the Streamlit app by running the following command:

   ```bash
   streamlit run app.py
   ```

4. **Access the app:**

   Open your browser and navigate to:

   ```
   http://localhost:8501
   ```

## Files and Directories
- `app.py`: The main file containing the app's source code.
- `logo.png`: The image logo used on the app's home page.
- `requirements.txt`: The Python dependencies required for running the app.
- `README.md`: This file.

## Data Source
All data is sourced from [CoinMarketCap](https://coinmarketcap.com).

## How to Use
1. **Select the currency**: Choose the currency unit (USD or BTC) for displaying cryptocurrency prices.
2. **Select cryptocurrencies**: Choose the cryptocurrencies you want to display from the sidebar.
3. **Select a time frame**: Choose the time frame (1 hour, 24 hours, or 7 days) for displaying the percentage change of cryptocurrencies.
4. **Download CSV**: You can download the price data of the selected cryptocurrencies by clicking the "Download CSV File" link.

## Credits
- **Author**: `<Prafull Raj>`
- **Data Source**: [CoinMarketCap](https://coinmarketcap.com)

## License
This project is licensed under the MIT License.
