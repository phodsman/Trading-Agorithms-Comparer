# Trading-Agorithms-Comparer

This program compares several different parameter amounts and machine learning models to test algorithmic trading on a hypothetical price history dataset.

## Technologies

This program was written in Python 3.7 and can be run in Jupyter Lab.

The following libraries are used:

- pandas
- numpy
- pathlib
- hvplot
- matplotlib
- sklearn

## Installation Guide

You will need to verify that you have installed the libraries listed in the Technologies section.

## Usage

The application `machine_learning_trading_bot.ipynb` can be run in Jupyter Lab. 

## Contributors
This program was written by Preston Hodsman based on a request for analysis from Trilogy Education Services, a 2U, Inc.

## License
MIT



## Report:

Four tests were run.

Results of the first test. 

Parameters: 

model: SVM

short_window = 4

long_window = 100

training data with an offset of 3 months

![](https://github.com/phodsman/Trading-Agorithms-Comparer/blob/main/Screenshot%202022-01-06%20124313.png?raw=true)

Results of the second test.

Parameters:

model: SVM

short_window = 4

long_window = 100

training data with an offset of 4 months

![](https://github.com/phodsman/Trading-Agorithms-Comparer/blob/main/Screenshot%202022-01-07%20080510.png?raw=true)

Results of the third test

Parameters:

model: SVM

short_window = 10

long_window = 30

training data with an offset of 4 months

![](https://github.com/phodsman/Trading-Agorithms-Comparer/blob/main/Screenshot%202022-01-07%20080753.png?raw=true)

Out of these three tests, it seems the two attempts at different parameters did not improve the performance on this dataset.

Results of the fourth test

Parameters: 

model: Adaboost

short_window = 4

long_window = 100

training data with an offset of 3 months

![](https://github.com/phodsman/Trading-Agorithms-Comparer/blob/main/Screenshot%202022-01-07%20080753.png?raw=true)

It appears that AdaBoost did improve the performance of the model compared to SVM.