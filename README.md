# Stock Data Visualizer

A Python application that visualizes stock data using AlphaVantage API and Pygal.

## Features
- Intraday, Daily, Weekly, and Monthly time series data.
- Bar and Line chart visualization.
- Saves charts as SVG files in the Downloads folder.
- Automatically opens generated charts in the web browser.

## Setup

1. Install dependencies:
   ```bash
   pip install requests pygal
   ```

2. Get a free API key from [AlphaVantage](https://www.alphavantage.co/support/#api-key).

3. Update `app.py` with your API key:
   ```python
   api_key = "YOUR_API_KEY_HERE" 
   ```

## Usage

Run the application:
```bash
python3 app.py
```
Follow the on-screen prompts to enter the stock symbol, chart type, time series, and date range.
