# prophet-challenge
Module 8 Challenge

# Forecasting Net Prophet

You’re a growth analyst at MercadoLibre. With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America. You've been tasked with analyzing the company's financial and user data in clever ways to make the company grow. So, you want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

## Introduction

The code provided here addresses the task of forecasting search traffic for MercadoLibre using the Prophet library. The steps involved in this analysis are detailed below:

### Steps:
1. Find unusual patterns in hourly Google search traffic.
2. Mine the search traffic data for seasonality.
3. Relate the search traffic to stock price patterns.
4. Create a time series model with Prophet.

## Steps Overview:

### Step 1: Find Unusual Patterns in Hourly Google Search Traffic
This step involves analyzing hourly Google search traffic for MercadoLibre, particularly focusing on the month of May 2020 when MercadoLibre released its quarterly financial results.

### Step 2: Mine the Search Traffic Data for Seasonality
This step involves mining the search traffic data to identify patterns of interest in the company by analyzing hourly traffic patterns, traffic by the day of the week, and traffic by the week of the year.

### Step 3: Relate the Search Traffic to Stock Price Patterns
This step explores the relationship between search traffic data and stock price patterns for MercadoLibre. It includes analyzing stock price data, comparing trends, and identifying correlations between search traffic and stock volatility.

### Step 4: Create a Time Series Model with Prophet
Finally, a time series model is constructed using Prophet to forecast search traffic patterns for MercadoLibre. The model is trained on historical search data and used to make predictions for future search traffic.

## Dependencies
The following Python libraries are required to run the code:
- Prophet
- pandas
- matplotlib
- datetime
- numpy
