# Financial Web Scraping and Data Analysis

This project aims to scrape financial data from a website and perform data analysis on the scraped data. It provides functionalities to retrieve stock prices, economic indicators, and news articles related to the financial domain. The scraped data can be used for various purposes, such as investment decision-making, trend analysis, and generating reports.

## Features

- **Scrape Stock Prices**: Retrieve the latest stock prices of a specified set of companies.
- **Scrape Economic Indicators**: Get the latest economic indicators, including values and percentage changes.
- **Scrape Financial News**: Fetch recent news articles related to the financial domain.
- **Analyze Stock Data**: Perform analysis on the scraped stock data.
- **Generate Reports**: Generate reports based on the scraped data.
- **Save Data to Database**: Store the scraped data in a database for further use.
- **Run Analysis**: Run custom analysis on the scraped data.

## Prerequisites

- Python 3.x
- Required Python packages: `beautifulsoup4`, `requests`, `pandas`, `numpy`, `matplotlib`, `sqlite3`

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/financial-web-scraper.git

2. Change to the project directory::

cd financial-web-scraper

3. Install the required packages:

pip install -r requirements.txt

4. Usage

1. Configure the web scraping parameters in the config.py file.

2. Run the main script:

python main.py

3. Follow the instructions in the terminal to select the desired functionalities and view the scraped data or analysis results.

# Examples

Here are some examples of using the project functionalities:

stock_prices = get_stock_prices(['AAPL', 'GOOGL', 'AMZN'])
print(stock_prices)

analysis_results = analyze_stock_data(stock_data)
print(analysis_results)

report = generate_report(data)
print(report)

