# Simple Mean Reversion Strategy in Python
This script runs a procedure of 
* (i) comprehensive testing (7 tests) a selected trading pair for unit root and 
* (ii) subsequently backtesting this pair using zScore ratio. 

## Detailed content
This repository includes the Notebook, which contains two main modules:
1. Pair selection
   - Download and prepare a time-series
   - Calculate hedge ratio and spread
   - Test the spread for stationarity
     - Augumented Dickey Fuller
     - Phillips-Perron
     - Zivot-Andrews
     - KPSS
     - Variance Ratio
     - Hurst Exponent
     - Halflife
2. Pair backtest
   - Download time-series and prepare data frame for out-of-sample backtesting
   - Calculate rolling hedge ratio and zScore ratio
   - Create buy/sell signals based on zScore ratio
   - Calculate backtest metrics gross and net trading fees 

## Getting Started
* Install Python 3+
* Open Jupyter Notebook by typing 'jupyter notebook' in Command Prompt console.
* You may also install libraries by typing in the Command Prompt console 'pip install [name of the library]', e.g. pip install pandas'

## Built With

* [Python 3](https://www.python.org/) - The programming language used
* [Python libraries] - check the first cell in the notebook

## Authors

* **Piotr Arendarski, Ph.D.** - *Initial work* - [Simple Mean Reversion Strategy](https://github.com/PiotrArendarski/Simple-Mean-Reversion-Strategy-in-Python)

See also the list of [contributors](https://github.com/PiotrArendarski/Simple-Mean-Reversion-Strategy-in-Python) who participated in this project.

## License

TBA

## Acknowledgments

* https://www.pythonforfinance.net/ - inspiration and partial solutions
* https://www.quantstart.com/ - inspiration and partial solutions
* TBA
