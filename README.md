# Stock Price Predictor

This project is a web application built with Streamlit in Python for predicting the closing price of a particular stock. 

## Project Description

This Stock Price Predictor allows the user to select from a predefined list of stocks and uses historical stock data to make predictions about the closing price of the stock based on the opening price, highest price, lowest price, and volume of the stock on a particular day. 

Currently, it supports Google (GOOG), Bitcoin (BTC-USD), and Microsoft (MSFT). The prediction models supported include Linear Regression, Lasso Regression, and Ridge Regression.

## Installation 

This project requires Python and the following Python libraries installed:

- NumPy
- pandas
- matplotlib
- seaborn
- yfinance
- streamlit
- scikit-learn

You also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included.

To install the requirements with pip, run the following command:

```
pip install -r requirements.txt
```


## Usage

After you clone this repo to your desktop, go to its root directory and run `streamlit run app.py` to start the app.

