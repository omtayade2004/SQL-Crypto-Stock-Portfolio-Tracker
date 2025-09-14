SQL Crypto & Stock Portfolio Tracker  

A simple yet robust SQL database schema designed to track cryptocurrency and stock 
transactions. This project provides the necessary tables to log buys and sells, store historical 
price data, and run analytical queries to calculate portfolio holdings and simplified profit and 
loss (PnL). 

Features 
• Transaction Logging: Records BUY and SELL activities with quantity, price, and 
fees. 
• Price History: Stores daily Open, High, Low, Close (OHLC) price data for each asset. 
• Data Integrity: Uses primary and foreign keys to ensure relational consistency (with 
suggested users and securities tables). 
• Example Analytics: Includes powerful queries to calculate current holdings and 
realized PnL.

Database Schema 

The database consists of two primary tables: transactions and prices. For a more robust setup, 
it's designed to be linked with users and securities tables. 
• transactions: The core table that logs every trade. 
• prices: Stores daily price data for each security. 
• users: (Suggested) Stores user information. 
• securities: (Suggested) Stores information about each asset (e.g., BTC, ETH).
