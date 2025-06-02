# Currency-Exchange-Rate-Tracker-
An interactive Python project powered by Streamlit, designed to provide real-time currency insights and intelligent conversion tools for global users.

 <- Core Functionalities:
 #Live Rate Overview – Instantly fetch exchange rates for any currency
 ##Currency Converter – Convert between any two currencies using up-to-date data
 ###Multi-Currency Conversion – Convert one base amount to multiple currencies at once
 ####Historical Trends Visualization – Select currencies and plot exchange rates over time

-> Why It Stands Out:
#API caching, responsive layout, and advanced features for academic distinction
##Designed for real-world application and advanced Python evaluation

currency rate 3i/
│
├── main.py                  # Main Streamlit app
├── config.py                # API config and supported currency list
├── requirements.txt         # Python dependencies
├── README.md                # Project documentation
├── components/
│   ├── exchange_api.py      # Fetches live exchange rates
│   ├── converter.py         # Performs single currency conversions
│   ├── multi_converter.py   # Multi-currency conversion logic
│   ├── visuals.py           # Graphs and visualizations
│   └── predictor.py         # Forecasts future exchange rates
⚙️ Features
Feature	Description
🔄 Live Rates	View all supported currencies with their real-time exchange rates
💰 Currency Converter	Convert any amount from one currency to another using live data
📊 Exchange Rate Trends	Interactive bar charts visualizing rate changes
🌍 Multi-Currency Conversion	Convert one base currency to several currencies at once
🔮 Rate Prediction	Predicts future exchange rates using linear regression

🧪 Requirements
Install the required Python packages:
pip install -r requirements.txt

🚀 Run the App
streamlit run main.py
The app will launch in your default web browser.

📡 API Configuration
Edit the config.py file to add your own ExchangeRate-API key:

python

API_KEY = "your_api_key_here"
🧠 How Predictions Work
The forecast uses basic Linear Regression on synthetic historical data to predict exchange rate trends. It is for demonstration purposes and not financial advice.



