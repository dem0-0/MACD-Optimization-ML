# MACD Indicator Optimization with ML

## Project Description
* Buy signals generated by the MACD indicator's histogram is optimized. 
* Data Service contains a script to automatically collect historical candle data
* Algorithms implemented from scratch: 
    - __Logistic Regression__ with L2 Regularization, Mini-Bacth & Stochastic Gradient Descend and Class Weights
    - __K-Nearest Neighbors__ with Cosine Similarity, Euclidean Distance, Manhattan Distance
    - __Naïve Bayes Classifier__ (Categorical and Gaussian)
* Most of the pre-processing pipeline will be kept confidential as well as the features used
* More detailed information can be find at reports/Final_Report.pdf

## Installation
### Dependencies
This project is implemented in Python 3 \
Python packages used can be found in requirements.txt \
Using the exact versions of the dependencies is recommended to avoid bugs & errors 
### Setup
* __On Linux:__
  - Run "make install" if Python 3 is not installed
  - Run "make init" to initialize a virtual environment with dependencies installed
  - You may use "make run" in order to run the main file
