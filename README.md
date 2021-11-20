<img align="center" src="https://miro.medium.com/max/4096/1*WtZDnrVjk4sPoNc4Br1Hvw.jpeg" height=300>

# Stock Market Prediction
A python web application created with python and flask to predict stock prices for the next 7 days for any stock input by user available under NASDAQ (National Association of Securities Dealers Automated Quotations) or NSE (National Stock Exchange of India Ltd.).
Predictions are made using LSTM, ARIMA, and Linear Regression algorithms along with sentiment analysis of tweets regarding the specific stock.

## What my application does
When a user enters a stock (from NASDAQ or NSE) as input, the predictions for the nest 7 days are generated with a recommendation of whether the stock price is going to rise or fall. To try it yourself, view it here: [Demo Website](https://aryan-stock-market-prediction.herokuapp.com/)

## File structure
| File Name        | Description                       |
|------------------|-----------------------------------|
| app              | all necessary files for flask app |
| wsgi.py          | file to run the app               |
| requirements.txt | all required packages             |

## How to use
1. Clone the repository to your system with `git clone https://github.com/AryanWadhawan08/Stock-Market-Prediction.git`
2. Open the terminal in the cloned directory with `cd Stock-Market-Prediction`
3. Install the requirements with `pip install -r requirements.txt` (for windows) or `pip3 install -r requirements.txt` (for linux/mac)
4. Run [wsgi.py](/wsgi.py) with `python wsgi.py` (for windows) or `python3 wsgi.py` (for linux/mac)

## License
[MIT](/LICENSE)


