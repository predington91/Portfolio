# S&P 500 Future Contracts Prediction Project

## Table of Contents
- [Overview](#overview)
- [Built With](#built-with)
- [Features](#features)
- [Contact](#contact)
- [References](#references)

## Overview
This project focuses on predicting short-term price actions for S&P 500 future contracts (/ES symbol). The objective is to streamline the prediction process and enhance trading strategies by forecasting movements within a 5-minute timeframe. With the end goal of beining implemented into binary logic gates to be used in a intra-day trading algorithm

## Built With
- Python
- Scikit-Learn
- XGBoost
- CatBoost

## Features
- Utilizes Kaggle's "Intraday market data" from February 2020 to July 2023.
- Extracts key features (/ES, /ES Volume) and converts them into 5-minute candlesticks.
- Computes various technical indicators, including SMA, EMA, Bollinger Bands, MACD, Stochastic Oscillator, and Fibonacci retracements.
- Implements logistic regression models for predicting binary price movements.
- Evaluates models' performance using accuracy and precision metrics.

## Contact
For any inquiries, please contact Patrick Redington at predington91@gmail.com.

## References
- Data Source: [Intraday market data](https://www.kaggle.com/datasets/brtnsmth/intraday-market-data) by Barton-Smith.
- References:
  - [Bollinger Bands®: What they are, and what they tell investors](https://www.investopedia.com/terms/b/bollingerbands.asp)
  - [How to calculate Moving average convergence divergence (MACD)](https://www.investopedia.com/ask/answers/122414/what-moving-average-convergence-divergence-macd-formula-and-how-it-calculated.asp)
  - [Stochastic oscillator: What it is, how it works, how to calculate](https://www.investopedia.com/terms/s/stochasticoscillator.asp)
  - [What are Fibonacci retracements and Fibonacci ratios?](https://www.investopedia.com/ask/answers/05/fibonacciretracement.asp)

