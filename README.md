# StockPrediction
A stock forecasting website. The users can view historical stock data, real-time stock data and do prediction utilizing SVM, ANN, Bayesian curve fitting, Lasso/Ridge. We have three indicators: SMA, EMA, RSI.

## Getting Started
1. We use Python as serverside language, if you haven't install Python, first go there https://www.python.org/ to download and install Python 2.7
2. We use MongoDB as database, if you haven't install MongoDB, first go there https://www.mongodb.com/ to download and install it.
3. Simply use git command:
  ```
	git clone https://github.com/marlonli/StockPrediction.gi
  ```
to clone the repository or download ZIP documents.
4. Install Python packages, direct to StockPrediction/server run command:
  ```
	pip install -r requirements.txt
  ```
5. Install front-end requirements, run:
  ```
	npm install
  ```
6. Restore data, direct to StockPrediction/Data, run command:

```
mongorestore --drop --db StockAnnual dump/StockAnnual
mongorestore --drop --db StockRealtime dump/StockRealtime
```

6. Start server, direct to project directory, run command:
  ```
	python index.py
  ```
7. Open local browser, enter url:

	http://localhost:5000
  
