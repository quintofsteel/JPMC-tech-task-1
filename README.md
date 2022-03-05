
# Interface with a stock price data feed and, analysis of the data
<b>Processing the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur</b>

## Set up / Installation
<p>To start the server, run</p>

	`python server3.py`

This will create random market called 'test.csv' in your working directory if one does not already exist.

- If you encounter an issue with `datautil.parser`, run this command: 

	`pip install python-dateutil`

- If you don't have pip yet, you can install it from: https://pip.pypa.io/en/stable/installing/

- To start the example client, run:

	`python client3.py`

- To unit test the example client, run:
	`python client_test.py`

