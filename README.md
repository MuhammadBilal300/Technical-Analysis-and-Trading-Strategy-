# **WLD Coin Trading Strategy**

This project implements a trading strategy for **WLD Coin** using historical price data. It provides automated buy and sell signals based on a technical analysis strategy incorporating moving averages, the RSI (Relative Strength Index), and leverage-based trading for futures markets.

## **Table of Contents**
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Setup and Installation](#setup-and-installation)
4. [How to Run the Project](#how-to-run-the-project)
5. [Technical Indicators and Strategy](#technical-indicators-and-strategy)
6. [Example Output](#example-output)
7. [License](#license)

---

## **Project Overview**

This project is a Python-based trading bot for **WLD Coin**, focusing on futures trading with a leverage of 5x. The core strategy utilizes common technical indicators like Moving Averages (MA) and RSI to determine buy and sell signals. The bot simulates trades using a given historical dataset from **CoinMarketCap**, tracks the wallet balance, and includes a risk management system with stop-loss and take-profit levels.

Key features include:
- Automated buy/sell signal generation.
- Risk management with stop-loss and take-profit levels.
- Leverage-based trading (5x leverage).
- Wallet balance tracking.
- Output of trades and results into a CSV file for detailed analysis.

---

## **Features**

- **Position Size Calculation**: This system manages risk by calculating the correct position size based on a $3000 wallet balance and leverage trading.
- **Buy and Sell Signals**: The strategy generates buy and sell signals, and manages open positions with pre-defined stop loss and take profit levels.
- **Technical Indicators**: The strategy employs 20-day and 50-day Exponential Moving Averages (EMA) as well as the Relative Strength Index (RSI).
- **Backtest on Historical Data**: Trades are simulated based on past data to calculate potential profit or loss.

---

## **Setup and Installation**

### **Prerequisites**
To run this project, you will need the following tools and libraries installed:
- **Python 3.7 or higher**
- **Pandas** for data handling
- **TA-Lib** for calculating technical indicators
- **Matplotlib** for plotting graphs (if you wish to visualize the strategy)
- **Numpy** for numerical operations

### **Step-by-Step Installation Guide**

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/WLD-Coin-Trading-Strategy.git
   cd WLD-Coin-Trading-Strategy
