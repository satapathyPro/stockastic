# Stockastic
### Predicting Stocks with ML

Stockastic is an ML-powered stock price prediction app built with Python and Streamlit. It utilizes machine learning models to forecast stock prices and help investors make data-driven decisions.

## How It's Built

Stockastic is built with these core frameworks and modules:

- Streamlit - To create the web app UI and interactivity 
- YFinance - To fetch financial data from Yahoo Finance API
- StatsModels - To build the ARIMA time series forecasting model
- Plotly - To create interactive financial charts

The app workflow is:

1. User selects a stock ticker
2. Historical data is fetched with YFinance
3. ARIMA model is trained on the data 
4. Model makes multi-day price forecasts
5. Results are plotted with Plotly

## Key Features

- Real-time data - Fetch latest prices and fundamentals 
- Financial charts - Interactive historical and forecast charts
- ARIMA forecasting - Make statistically robust predictions
- Backtesting - Evaluate model performance
- Responsive design - Works on all devices

## Getting Started

### Local Installation

1. Clone the repo

```bash
git clone https://github.com/satapathyPro/stockastic.git
```

2. Install requirements

```bash
pip install -r requirements.txt
```

3. Change directory
```bash
cd streamlit_app
```

4. Run the app

```bash
streamlit run 00_Main.py
```

The app will be live at http://localhost:8