# Peer-graded-Assignment-Analyzing-Historical-Stock-Revenue-Data-and-Building-a-Dashboard
Peer-graded Assignment: Analyzing Historical Stock/Revenue Data and Building a Dashboard
# Analyzing Historical Stock and Revenue Data and Building a Dashboard

## Overview

This repository contains my solution for the peer-graded assignment where, as a data scientist working for an investment firm, I extracted historical stock and revenue data for Tesla and GameStop. The objective is to analyze this data and create interactive dashboards that compare stock price trends with the corresponding revenue data.

## Project Requirements

This assignment is broken down into the following tasks:

- **Question 1:** Extract Tesla stock data using `yfinance` (2 Points)
- **Question 2:** Extract Tesla revenue data using webscraping (1 Point)
- **Question 3:** Extract GameStop stock data using `yfinance` (2 Points)
- **Question 4:** Extract GameStop revenue data using webscraping (1 Point)
- **Question 5:** Build a dashboard for Tesla that integrates both stock and revenue data (2 Points)
- **Question 6:** Build a dashboard for GameStop that integrates both stock and revenue data (2 Points)
- **Question 7:** Share the complete assignment notebook and screenshots (2 Points)

## Data Sources

- **Stock Data:** Extracted via the [yfinance](https://pypi.org/project/yfinance/) library.
- **Revenue Data:** Extracted from online sources using webscraping techniques with libraries such as `BeautifulSoup` and `requests`.

## Tools and Libraries

- Python 3.x
- Jupyter Notebook
- Pandas
- Plotly (for interactive visualizations)
- yfinance
- BeautifulSoup & requests (for webscraping)

## Notebook Structure

The Jupyter Notebook (`Final_Assignment.ipynb`) is organized as follows:

1. **Tesla Data Extraction:**
   - **Stock Data:** Creation of the Tesla Ticker object and extraction of historical stock data.
   - **Revenue Data:** Code to scrape Tesla revenue data from a designated webpage.

2. **GameStop Data Extraction:**
   - **Stock Data:** Creation of the GameStop (GME) Ticker object and extraction of historical stock data.
   - **Revenue Data:** Code to scrape GameStop revenue data.

3. **Dashboard Development:**
   - **Tesla Dashboard:** An interactive dashboard that integrates Tesla's stock and revenue data.
   - **GameStop Dashboard:** A similar dashboard for GameStop.
   - Visualizations include interactive line charts for stock prices and bar charts or additional plots for revenue or volume trends.

4. **Analysis and Insights:**
   - Markdown sections highlight key insights, trends, and any comparisons between the companies.
   - Screenshots of the final dashboards have been included to demonstrate the working outcomes.

## How to Run the Notebook

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/<your-username>/final_assignment_notebook.git
