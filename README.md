# Stock Portfolio Tracker

A beginner-friendly stock portfolio tracker built with Python, Flask, HTML, and CSS.

## Features
- Add a stock and quantity
- Calculate investment per stock and total investment
- Remove a stock from the table
- Download the portfolio as a CSV file
- Responsive layout for desktop and mobile

## Sample stock prices
The prices in this project are predefined sample values, not live market prices.

## Run locally
1. Install Python.
2. Open a terminal in this project folder.
3. Install dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

4. Start the app:

   ```bash
   python app.py
   ```

5. Open http://127.0.0.1:5000 in your browser.

## Deployment
This project includes `requirements.txt` and `Procfile` for hosting providers that support Flask and Gunicorn. Follow your hosting provider's instructions to connect the GitHub repository and deploy.

## Important note
Portfolio entries are kept in memory while the app is running. They can reset when the app restarts. This starter project does not use a database or live market data.
