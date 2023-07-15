# Genetic-Algorithm-for-Financial-Portfolio-Optimization

## Table of Contents
1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Contributing](#contributing)
7. [License](#license)

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
