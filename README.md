# Portfolio Optimization Tool

## Overview

The Portfolio Optimization Tool is a Python-based application that utilizes Mean-Variance Optimization (MVO) to help investors construct an optimal portfolio. The tool allows users to input a list of stocks, fetch historical price data, and calculate the best asset allocation that maximizes the Sharpe Ratio while minimizing risk.

## Problem Statement

Develop a Portfolio Optimization Tool that allows users to input a list of stocks, their historical prices, and investment constraints. The tool calculates the optimal asset allocation based on user-defined parameters.

## Features

- Fetch historical stock prices using Yahoo Finance.
- Calculate expected returns and risk (volatility) using historical data.
- Optimize portfolio allocation using Mean-Variance Optimization.
- Display portfolio performance metrics such as expected return, volatility, and Sharpe Ratio.
- Visualize the efficient frontier of optimal portfolios.

## Technologies Used

- Python
- Libraries: `numpy`, `pandas`, `matplotlib`, `yfinance`, `PyPortfolioOpt`
