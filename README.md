
# Stock Data Analysis Web App
# Description

This project is a Flask-based web application that enables users to analyze historical stock data by entering a company symbol along with a date range. The application fetches real-time stock data, performs data cleaning, conducts exploratory data analysis (EDA), and generates visualizations to help users understand stock trends.

It is built using Python, Flask, Pandas, Matplotlib, and the Yahoo Finance API (yfinance), providing a simple and interactive interface for financial data analysis. 

# Features

Fetch real-time stock data using Yahoo Finance API
Perform data cleaning and preprocessing
Generate summary statistics of stock data
Compute correlation matrix between features
Visualize stock closing price trends
Simple and user-friendly web interface

# Working
# 1. User Input

The user enters the company symbol, start date, and end date through a web form interface. 


# 2. Backend Processing

The Flask application processes the input and performs the following steps: 

Fetches stock data using the yfinance library

Cleans the dataset by removing missing values

Performs exploratory data analysis using statistical summaries and correlation matrix

Generates a visualization of stock closing prices over time

# 3. Data Visualization

The application creates a line plot of the stock's closing price and converts it into a format that can be displayed on the web page.

# 4. Result Display

The processed data, including summary statistics, correlation matrix, and visualization, is displayed on the result page. 

result

# Workflow

User Input → Data Fetching → Data Cleaning → Exploratory Data Analysis → Visualization → Result Display

# Tech Stack

Frontend: HTML, CSS
Backend: Flask (Python)
Libraries: Pandas, Matplotlib, Seaborn, yfinance

# Use Cases

Stock trend analysis for beginners
Learning project for data analysis and web development
Basic financial data visualization

# Future Improvements

Add machine learning-based stock prediction
Integrate interactive charts using Plotly
Support comparison of multiple stocks
Deploy application on cloud platforms such as AWS or Render
