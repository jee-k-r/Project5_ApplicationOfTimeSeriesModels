# Project5_ApplicationOfTimeSeriesModels
Acadgild's Masters in Data Science Course Project 5 Application of TimeSeries Models

# Dataset Link

https://drive.google.com/file/d/1pP0Rr83ri0voscgr95-YnVCBv6BYV22w/view

Hint:

import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

from pandas.tools.plotting import autocorrelation_plot

from statsmodels.graphics.tsaplots import plot_pacf

from statsmodels.tsa.arima_model import ARIMA, ARMAResults

import datetime

import sys

import seaborn as sns

import statsmodels

import statsmodels.stats.diagnostic as diag

from statsmodels.tsa.stattools import adfuller

from scipy.stats.mstats import normaltest

from matplotlib.pyplot import acorr

plt.style.use('fivethirtyeight')

%matplotlib inline

df = pd.read_csv('C:/Users/Downloads/sp500/data_stocks.csv')

df.head()

# Problem Statement:

Pick up the following stocks and generate forecasts accordingly

Stocks:
1. NASDAQ.AAPL
2. NASDAQ.ADP
3. NASDAQ.CBOE
4. NASDAQ.CSCO
5. NASDAQ.EBAY
