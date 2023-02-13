Algorithmic Trading Strategy Jupyter Notebook
Introduction
This Jupyter Notebook provides a simple algorithmic trading strategy that fetches intraday US stock data from Alpha Vantage using an API key. The script is written using Python and implements a class ScriptData that contains various methods for fetching, converting and manipulating the data.

Requirements
The following software and libraries are required to run the code in this Jupyter Notebook:
Python 3
Jupyter Notebook
Alpha Vantage API key (can be obtained for free from Alpha Vantage)
Pandas library
Requests library


Class ScriptData
The ScriptData class contains the following methods:
fetch_intraday_data: fetches intraday data for a given script (e.g. "GOOGL", "AAPL").
convert_intraday_data: converts the fetched intraday data into a pandas DataFrame with columns: timestamp, open, high, low, close, volume.
getitem, setitem, and contains methods for overload operations.
The data can be accessed using the following syntax:

script_data = ScriptData()
script_data.fetch_intraday_data('GOOGL')
script_data.convert_intraday_data('GOOGL')
script_data['GOOGL']

The output will be a pandas DataFrame with the same format as described above.



Conclusion
This Jupyter Notebook provides a simple algorithmic trading strategy that allows users to fetch intraday US stock data from Alpha Vantage and manipulate it as a pandas DataFrame. The code can be easily modified and extended for more complex algorithmic trading strategies.
