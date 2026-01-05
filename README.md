# Futures-Trend-Following-Risk-Management-CTA-Style-
Developed a systematic trend-following strategy using time-series momentum and volatility targeting across liquid futures proxies. The framework applies dynamic position sizing, leverage constraints, and drawdown controls to evaluate risk-adjusted performance in a CTA-style trading setup.


Project 3: Futures Trend-Following & Risk Management (CTA-Style Strategy)

This project implements a systematic futures trend-following strategy inspired by Commodity Trading Advisor (CTA) and managed futures frameworks. The strategy uses time-series momentum signals to identify persistent trends across major asset classes and applies volatility targeting to dynamically size positions while controlling portfolio risk.

Liquid ETF proxies for futures markets are used to ensure reproducibility, including equity index, fixed income, and commodity exposures. Positions are scaled inversely to realized volatility, capped by a leverage constraint, and combined into a diversified multi-asset portfolio. A portfolio-level drawdown control is incorporated to reduce downside risk during adverse market regimes.

Performance is evaluated using cumulative returns, annualized return, volatility, Sharpe ratio, and maximum drawdown, with equity curve and drawdown visualizations. The project demonstrates how trend-following strategies can be implemented with institutional-style risk management principles, emphasizing robustness, capital preservation, and disciplined execution.

Key Features

Time-series momentum (trend-following) signal

Volatility-targeted position sizing

Leverage constraints to limit risk exposure

Portfolio-level drawdown stop mechanism

Multi-asset diversification using futures proxies

Comprehensive performance and risk metrics
