# Stock Data Extraction and Visualization

## Project Overview
This project is designed to extract stock market data using the `yfinance` library and web scraping techniques, and then visualize the extracted data using `plotly`. The goal is to help users retrieve and analyze stock price trends efficiently.

## Features
- Fetch historical stock data using `yfinance`.
- Scrape financial data from the web.
- Visualize stock price trends using `plotly`.
- Support for multiple stock tickers.

## Technologies Used
- Python
- `yfinance` for stock data extraction
- Web scraping techniques (`BeautifulSoup`, `requests`)
- `plotly` for interactive visualizations

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/lucas-ncr/Analyzing_Tesla_and_GameStop_stock_history
   ```
2. Navigate to the project directory:
   ```sh
   cd stock-data-extraction
   ```
3. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Run the script to fetch and visualize stock data:
   ```sh
   python main.py
   ```
2. Enter the stock ticker symbol when prompted.
3. View the interactive graph in your web browser.

## Example Output
After running the script, the program will generate an interactive stock price chart using `plotly`, allowing users to analyze historical price trends.

## Contributing
Feel free to fork the repository and submit pull requests to enhance functionality or fix issues.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

