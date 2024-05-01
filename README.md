# PythonInvest - Comparing Trading Strategies 


## Overview
The notebook aims to explore and evaluate different trading strategies using historical price data of Amazon (AMZN) stock. It leverages the Backtrader library, a popular Python framework for backtesting and trading strategy development. The main objective is to explore different trading strategies and compare their performance through backtesting.

## Key Components
Strategy Development:
 - Several trading strategies are implemented as classes inheriting from the bt.Strategy class provided by Backtrader. These strategies include:

1. Moving Average Crossover
2. Exponential Moving Average (EMA) Crossover
3. RSI Mean Reversion
4. Parameter Optimization: A grid search approach is employed to find optimal parameters for the trading strategies. This involves iterating over different combinations of strategy parameters and selecting the parameters that yield the highest returns.

Backtesting: 
- The strategies are backtested using historical data to evaluate their performance over a specified period. Backtrader is used to simulate trading based on the defined strategies and parameters.

Performance Evaluation:
- Various performance metrics, such as initial and final portfolio values, percentage returns, and average returns, are calculated to assess the effectiveness of each strategy.

Visualization: 
- The performance of each strategy is visualized using candlestick charts, providing insights into the trading signals generated and the resulting portfolio value changes over time.

## TODO
1. Apply the strategies to diffrerent stocks and see how they compare.
