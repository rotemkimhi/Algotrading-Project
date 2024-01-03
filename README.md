# Algotrading-Project
Chaos Theory in Stock Market Analysis: Project Overview

Introduction:
The project explores the application of chaos theory in stock market analysis, leveraging mathematical models and indicators to identify trends. Chaos theory, rooted in mathematics, suggests that seemingly random events in dynamic systems can be understood through underlying patterns. The indicators tested include the Hurst Exponent, Fractal Adaptive Moving Average (FRAMA), Detrended Price Oscillator (DPO), and Chaikin Volatility Indicator.

Motivation:
Motivated by studies showing the effectiveness of chaos theory in predicting stock market trends, the project aims to challenge traditional technical indicators. Inspired by experiments like the Moving Hurst (MH) indicator, which outperformed MACD, the team focuses on chaos theory to potentially provide more robust trading signals.

Methodology:
1. Data Collection: Gathered 15 years of Tel Aviv Stock Market 125 data (2006-2021) for over 100 stocks.
2. Indicators: Created indicators like Hurst, FRAMA, DPO, and CO based on mathematical models.
3. Time Division: Segregated data into IN (2016-2018) and OUT (2019-2021) groups for testing.
4. Parameter Examination: Analyzed market trends using indicators, emphasizing the impact of Hurst values on stock trends.
5. Strategy Building: Developed a dynamic strategy using wallet division and incorporating stop-loss tests.
6. Optimization: Utilized optimization techniques to enhance the Sharpe ratio and improve the model's performance.
7. Results Processing: Calculated standard deviation, Sharpe ratio, and return per share for portfolio evaluation.
8. Train-Test Model: Utilized machine learning (HistGradientBoostingClassifier) to predict future stock returns.

Results and Conclusions:
- The project encountered challenges in achieving desired Sharpe ratios, leading to ongoing refinement of strategies.
- The model demonstrated potential improvements through optimizing time windows, running train-test cycles, and adjusting wallet distribution.
- Continuous work is planned to enhance the model's performance and achieve higher Sharpe ratios, aligning with the motivation to showcase chaos theory's effectiveness in stock market analysis.

Future Work:
1. Explore dynamic optimization time windows for more accurate results.
2. Implement periodic train-test cycles to recommend updated stock portfolios.
3. Optimize wallet distribution based on weighted strategies.
4. Refine stop-loss tests to further protect the portfolio.
5. Evaluate the model's performance against different market conditions.

Conclusion:
The project, rooted in chaos theory, aims to revolutionize stock market analysis. Despite initial challenges, ongoing improvements and refinements are anticipated to enhance the model's ability to predict trends, offering valuable insights for traders in the dynamic stock market landscape.

