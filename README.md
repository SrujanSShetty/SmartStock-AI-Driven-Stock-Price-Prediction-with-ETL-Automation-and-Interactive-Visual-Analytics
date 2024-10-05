SmartStock: AI-Driven Stock Price Prediction :Using Deep Learning, ETL, SQL, and Power BI

Overview

This project predicts future stock prices by using historical data scraped from the web. We automate the process of gathering, cleaning, and storing stock data in a SQL database, train a deep learning model to predict future prices, and visualize the results in Power BI.

Technologies Used

	•	Python: Web scraping, ETL, data processing, and model building.
	•	ETL Pipeline: Custom pipeline using pandas and SQLAlchemy.
	•	SQL: MySQL/PostgreSQL for storing and retrieving stock data.
	•	Deep Learning: TensorFlow/Keras for stock price predictions.
	•	Power BI: Visualization of stock trends and predictions.

How It Works

	1.	Web Scraping: Automatically extract historical stock data using Python’s requests and BeautifulSoup.
	2.	ETL Pipeline: Clean, transform, and load data into a SQL database using pandas and SQLAlchemy.
	3.	Data Storage: Store the cleaned data in MySQL or PostgreSQL.
	4.	Deep Learning Model: Train a model using TensorFlow/Keras to predict future stock prices based on historical data.
	5.	Visualization: Use Power BI to create interactive dashboards that display predictions and trends.

Results

	•	Predicts stock prices based on historical data.
	•	Automatically collects, processes, and stores stock data.
	•	Generates clear, interactive visualizations using Power BI.

Innovation

Combines automation (ETL pipeline), deep learning, and interactive analytics to create an end-to-end stock prediction solution.

How to Run the Project

	1.	Install dependencies: pip install -r requirements.txt
	2.	Set up your SQL database (MySQL/PostgreSQL).
	3.	Run the web scraping and ETL pipeline.
	4.	Train the deep learning model.
	5.	Visualize the data in Power BI.
