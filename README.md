# Machine Learning in Finance 
## Trading Strategy Development

Date: 19 Nov 2018

## Description testing

Recently, Artificial Neural Networks (ANNs) have been widely applied to financial type problems such as trend direction and price prediction. The project utilizes a few machine learning algorithms to run the model. Some of them are feed-forward Artificial Neural Network (ANN), Long Short-Term Memory (LSTM), Support Vector Machine (SVM) and Naive Bayes. The best model that gives the highest score on a few performance metrics will be used to run the trading process. For instance, the Naïve Bayes model will predict stock prices by fitting featured engineering techniques or other technical indicators into the model. Some of the input features includes Simple Moving Average (SMA), Moving Average Convergence Divergence (MACD), Exponential Moving Average (EMA), Relative Strength Index (RSI), Momentum (MOM), Rate of change (ROC) and other time series factors. The output of the model is used as signals and then imported to the ‘Backtrader’ python backtesting system. The results of the backtesting process are analyzed using ‘Pyfolio’, a Python library for performance and risk analysis of financial portfolios. 

## Prerequisites: Python

While Jupyter runs code in many programming languages, Python is a requirement (Python 3.3 or greater) for installing the Jupyter Notebook.

It is recommended to use the Anaconda distribution to install Python and Jupyter. 

Install the latest version of the Anaconda 3 distribution which must include an IDE like Spyder. This is the link to download the appropriate version for different operating systems: https://www.anaconda.com/download/

## Installation

After Anaconda is installed, Jupyter Notebook will be available to use. 

To run Jupyter Notebook from Terminal, run: jupyter notebook
(Normally jupyter.exe can be found in .../anaconda3/scripts/ directory)

From Jupyter Notebook: Open the file Groupwork Assignment Submission 3.ipynb and run it.

## Packages Used

Packages can be installed by running the following command in the terminal (project working directory): "pip install -r pip_requirements.txt" 

* fix-yahoo-finance==0.0.22
* pandas==0.22.0
* numpy==1.14.2
* backtrader==1.9.67.122
* pyfolio==0.9.0
* matplotlib==2.2.3
* seaborn==0.9.0
* pandas-datareader==0.7.0
* keras==2.2.4
* scikit-learn==0.20.0

## Notes

* This program was built by using Windows 10.
* Python 3.6.6 was used.
* Tested successfully on Windows 10.
