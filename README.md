# Sequential Decision Problem Modeling Library

This is a refactoring and evolution of the Sequential Decision Problem Modeling Library from Castle Lab, Princeton Univ. The goal is to make the problem code more structured, easily extendable, and more readable.

The major changes are:
- Introduction of abstract base classes `SDPModel` and `SDPPolicy` from which all sequential decision problems and policies inherit
- Jupyter Notebook with plotly as frontend

Furthermore, the code was cleaned up for readability and exercises were added to some of the Notebooks. 

## Installation

Requires Python 3 and the following packages:
- numpy
- scipy
- pandas
- plotly.express
- yfinance (for AssetSelling)
- osmnx (for StochasticShortestPath)
- networkx (for StochasticShortestPath)

## Included Problem Models

This is work in progress. For now, new models exist for 
- `AssetSelling`
- `MedicalDecisionDiabetes`
- `StochasticShortestPath_static`

Further models will be added in the future. The other folders contain the models from the original repository [https://github.com/wbpowell328/stochastic-optimization].

There is an `ipynb`-file in each problem folder which is the starting point for running the models.
