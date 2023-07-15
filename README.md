# Genetic-Algorithm-for-Financial-Portfolio-Optimization

## Table of Contents
1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Usage](#usage)

## Introduction

This Python-based project applies a genetic algorithm to optimize a portfolio of fintech stocks, using the Sharpe Ratio as a measure of performance. The portfolio optimization focuses on a list of predefined fintech stocks, including Visa, Mastercard, PayPal, and others.

A Moving Average Crossover strategy is employed, where two moving averages of different lengths are calculated, and trading signals are generated based on when the two averages cross. The genetic algorithm is used to find the optimal window sizes for the short and long-term moving averages to maximize the Sharpe Ratio.

The project includes the visualization of the algorithm's performance over iterations, presenting an interactive plot that shows the evolution of the fitness of the algorithm over generations.

## Prerequisites

The project requires the following Python packages:
- pandas: Data manipulation and analysis.
- yfinance: Downloading historical market data from Yahoo Finance.
- deap: Genetic and evolutionary algorithms.
- numpy: Numerical operations.
- matplotlib: Data visualization.
- ipywidgets: Interactive HTML widgets for Jupyter notebooks.

## Installation

To install the required packages, you can use pip:
```shell
pip install pandas yfinance deap numpy matplotlib ipywidgets
```
## Usage
Clone the repository:
```shell
git clone https://github.com/DhruvAjayToshniwal/Genetic-Algorithm-for-Financial-Portfolio-Optimization.git
```
Run the script:
```shell
python main.py
```
Upon execution, the script fetches historical data for the selected fintech stocks and applies a Moving Average Crossover strategy. The performance of this strategy is calculated, and a genetic algorithm is run to find the optimal short and long windows for the moving averages. The result is an interactive plot that shows the evolution of the algorithm's fitness over generations. Please note that the interactive plot feature requires a Jupyter Notebook or similar environment.

# Graphs
## Stock - V
![image](https://github.com/DhruvAjayToshniwal/Genetic-Algorithm-for-Financial-Portfolio-Optimization/assets/57616258/63ef6950-10e9-4097-b1d4-84bfd35bc789)

## Stock - MA
![image](https://github.com/DhruvAjayToshniwal/Genetic-Algorithm-for-Financial-Portfolio-Optimization/assets/57616258/be94eddf-b5c5-4c7d-b930-bbca910216b6)

## Stock - PYPL
![image](https://github.com/DhruvAjayToshniwal/Genetic-Algorithm-for-Financial-Portfolio-Optimization/assets/57616258/ba9c0d5e-199d-4101-af77-8978b5fb12d8)

## Stock - SQ
![image](https://github.com/DhruvAjayToshniwal/Genetic-Algorithm-for-Financial-Portfolio-Optimization/assets/57616258/5af042f7-db46-4b6b-b3aa-0f3a63b0175a)

## Stock - ADP
![image](https://github.com/DhruvAjayToshniwal/Genetic-Algorithm-for-Financial-Portfolio-Optimization/assets/57616258/e2c7ac08-6630-4b6c-9414-a28a35b21fac)

## Stock - GS
![image](https://github.com/DhruvAjayToshniwal/Genetic-Algorithm-for-Financial-Portfolio-Optimization/assets/57616258/39206465-caf6-4e41-8876-1da11c025d6e)

## Stock - MS
![image](https://github.com/DhruvAjayToshniwal/Genetic-Algorithm-for-Financial-Portfolio-Optimization/assets/57616258/efbf3c88-a57f-4d8c-a4a9-dae7eabcc1a1)

## Stock - JPM
![image](https://github.com/DhruvAjayToshniwal/Genetic-Algorithm-for-Financial-Portfolio-Optimization/assets/57616258/ab6ad69f-825f-4817-ac45-32d6acc80e38)
