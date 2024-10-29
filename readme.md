# Project Name: Financial Indicator Calculator with REST API Communication

## Project Overview
Create a simple financial web app that calculates a technical indicator from CSV data and displays it on a frontend. The project will involve:
- Creating a backend to read transaction data from a CSV file.
- Calculating a technical indicator (e.g., Rsi,MA,EMA,SMA,MACD).
- Exposing this data via REST endpoints.
- Consuming this data on the frontend and visualizing it using charts.

## Key Features

### Backend CSV Data Processing
- Read transaction data from a CSV file.
- Each record in the CSV should include fields like "amount," "category" (e.g., groceries, bills), and "date."

### Financial Indicator Calculation
Calculate a simple financial metric such as:
- **RSI:** Calculate the relative strength index.
- **MACD:** Calculate the Moving Average Convergent Divergent.

### REST Requests
Implement basic REST API endpoints to expose the calculated metrics:
- **GET:** Retrieve total spending or average spending by category.

### Frontend Data Visualization
- Use JavaScript and Chart.js to create a simple chart that visualizes the data retrieved from the backend.
- For example, display a bar chart showing spending per category.

## Tech Stack

### For AI Role
- **Backend:** Python or Node.js (Express)
- **Frontend:** HTML/CSS/JavaScript
- **Data Source:** CSV file for transaction data
- **API:** REST API to serve calculated financial metrics
- **Dockerized:** Must dockerize front and backend

### For SWE Role
- **Backend:** Rust
- **Frontend:** HTML/CSS/JavaScript
- **Data Source:** CSV file for transaction data
- **API:** REST API to serve calculated financial metrics
- **Dockerized:** Must dockerize front and backend

## Expected Learning Outcomes
- Understand how to read and process CSV data.
- Learn to make REST requests and handle API responses.
- Practice building a simple backend to communicate with a frontend.
- Visualize data using charts.

## Stretch Goals
- Add more technical indicators.
- Allow the user to upload their own CSV file for custom analysis.

## Estimated Time Frame
2-3 days for a basic version.

## Resources to Get Started
- [Flask Tutorial for Beginners](https://flask.palletsprojects.com/en/stable/tutorial/)
- [JavaScript Fetch API for Making REST Requests](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
- [Chart.js Documentation for Visualizing Data](https://www.chartjs.org/docs/latest/)
- [Python CSV Module Documentatio](https://docs.python.org/3/library/csv.html)n
- [7 Technical Indicators to Build a Trading Toolkit](https://www.investopedia.com/top-7-technical-analysis-tools-4773275)
- [Rust for Backend Development - Mastering Backend](https://masteringbackend.com/posts/rust-for-backend-development)
- [Docker for Beginners: Everything You Need to Know](https://www.howtogeek.com/733522/docker-for-beginners-everything-you-need-to-know/)
- [pandas-ta | Technical Analysis Indicators - Pandas TA is an easy to use Python 3 Pandas Extension with 150+ Indicators](https://twopirllc.github.io/pandas-ta/)
- [ta - Rust](https://docs.rs/ta/latest/ta/)
