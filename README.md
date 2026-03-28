# Hedge Fund Strategy Research Project

## Overview

This project presents a systematic trading strategy developed under a hedge fund–style research framework.

The focus is on:

- Alpha signal construction
- Risk-controlled portfolio formation
- Realistic backtesting methodology
- Performance and drawdown analysis

The strategy integrates quantitative modeling with practical trading considerations, including turnover, transaction costs, and stability across time.

---

## Methodology

1. Feature construction based on market data
2. Signal generation and normalization
3. Portfolio weighting under risk constraints
4. Rolling out-of-sample backtesting
5. Performance evaluation

Portfolio return:

R_t = sum(weight_i,t-1 * return_i,t)

Turnover:

Turnover_t = sum(abs(weight_i,t - weight_i,t-1))

---

## Performance Evaluation

Key metrics include:

- Annualized Return
- Annualized Volatility
- Sharpe Ratio
- Maximum Drawdown
- Stability across regimes

---

## Objective

The goal of this project is to demonstrate:

- Quantitative research capability
- Financial intuition behind alpha signals
- Proper backtesting discipline
- Implementation readiness for real trading environments

---

## Disclaimer

For academic and research purposes only.
