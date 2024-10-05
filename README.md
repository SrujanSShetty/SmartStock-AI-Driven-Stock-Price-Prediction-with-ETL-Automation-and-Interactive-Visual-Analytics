SmartStock: AI-Driven Stock Price Prediction : Using Deep Learning, ETL, SQL, and Power BI

1. Overview

This project predicts future stock prices by using historical data scraped from the web. We automate the process of gathering, cleaning, and storing stock data in a SQL database, train a deep learning model to predict future prices, and visualize the results in Power BI.

2. Technologies Used

	•	Python: Web scraping, ETL, data processing, and model building.
	•	ETL Pipeline: Custom pipeline using pandas and SQLAlchemy.
	•	SQL: MySQL/PostgreSQL for storing and retrieving stock data.
	•	Deep Learning: TensorFlow/Keras for stock price predictions.
	•	Power BI: Visualization of stock trends and predictions.

3. How to Run
1. Clone the repository: `git clone https://github.com/your-username/stock-market-prediction-deep-learning.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the scripts in order:
   - `web_scraper.py`: Scrapes stock data.
   - `etl_pipeline.py`: Cleans and transforms the data.
   - `deep_learning_model.py`: Trains the LSTM model.
4. Set up Power BI for visualization.

Results

	•	Predicts stock prices based on historical data.
	•	Automatically collects, processes, and stores stock data.
	•	Generates clear, interactive visualizations using Power BI.

Innovation

Combines automation (ETL pipeline), deep learning, and interactive analytics to create an end-to-end stock prediction solution.


