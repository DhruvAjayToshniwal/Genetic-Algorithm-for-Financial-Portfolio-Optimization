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
```
## Usage
Clone the repository:
```shell
Copy code
git clone https://github.com/<YOUR_GITHUB_USERNAME>/<YOUR_REPOSITORY_NAME>.git
```
Run the script:
```shell
Copy code
python main.py
```
Upon execution, the script fetches historical data for the selected fintech stocks and applies a Moving Average Crossover strategy. The performance of this strategy is calculated, and a genetic algorithm is run to find the optimal short and long windows for the moving averages. The result is an interactive plot that shows the evolution of the algorithm's fitness over generations. Please note that the interactive plot feature requires a Jupyter Notebook or similar environment.

## Project Structure
The project structure is as follows:

main.py: This is the main script that fetches the data, applies the trading strategy, and runs the genetic algorithm.
README.md: The file you're currently reading, which provides an overview of the project and instructions on how to use it.


