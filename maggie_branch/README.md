# Cryptocurrency Comparison and Prediction Project

This project aims to compare three cryptocurrencies and predict their future closing prices using historical data and machine learning techniques.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [API Sources](#api-sources)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
## Project Overview

This project involves:
- Collecting historical price data for three cryptocurrencies: Bitcoin (BTC), Ethereum (ETH), and Dogecoin (DOGE).
- Performing exploratory data analysis (EDA) to understand the data.
- Building and training machine learning models to predict future closing prices (Prophet).
- Visualizing the predictions and comparing the performance of different models.

## Features

- Data collection and preprocessing
- Exploratory Data Analysis (EDA)
- Machine learning models for price prediction (Linear Regression, LSTM)
- Visualization of historical prices and predictions

## API Sources

- APIs:
  - [Coinbase](https://login.coinbase.com/signin)
  - [Token Metrics](https://app.tokenmetrics.com/subscription/success)
  - [Yahoo](https://sg.finance.yahoo.com)

## Installation

To set up this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Sravya-Kottisa/Bootcamp_Project1_StockAnalysis/blob/main/README.md
    ```
2. Navigate to the project directory:
    ```bash
    cd crypto-comparison-prediction
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    pip install prophet
    ```
4. Import the necessary libraries in your Jupyter notebook:
    ```python
    import pandas as pd
    import datetime
    from prophet import Prophet
    import csv
    import time
    import os
    import matplotlib.pyplot as plt
    import numpy as np
    import json
    import requests
    ```

## Usage

1. Ensure you have the necessary data files in the `data/` directory.
2. Run the Jupyter notebook:
    ```bash
    jupyter notebook
    ```
3. Open the `working_project1-FINAL.ipynb` notebook and run the cells step-by-step to execute the analysis and prediction.


## Results

- All three cryptocurrencies showed tremendous growth over the past year, with Bitcoin's value increasing by over $30,000. This is due to a variety of reasons including "Halving Events", The approval of spot Bitcoin ETFs,Interest Rate Cuts, and investments from such companies as Tesla and Block, inc (formerly Square).

    - Ethereum's and Dogecoin's value is in part set by Bitcoin, but some other factors have also played a part in their rising values such as major updates to the Ethereum network (Ethereum 2.0), and Elon Musk's personal tweets endorsing Dogecoin. 

- The accuracy of the Prophet model in forecasting the 3 cryptocurrency 
prices varies

- On an average it achieved a precision of 94.5%

- The quality is dependent on various factors like, quality of data, 
complexity of the model and volatility of cryptocurrency market and 
other influences



