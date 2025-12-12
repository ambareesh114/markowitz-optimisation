Markowitz Portfolio Optimization – Efficient Frontier & Optimal Portfolios

This project implements Modern Portfolio Theory (MPT) using Python to construct and analyze optimal portfolios.
It includes efficient frontier visualization, Global Minimum Variance (GMV) portfolio, Maximum Sharpe Ratio (MSR) portfolio,
and utility-based optimization. All computations are modularized using a custom library: Risk_Kit.py.

1. Overview

The Markowitz framework provides a mathematical method for allocating capital across assets
to balance risk vs return. This notebook demonstrates:

    1.1 Efficient frontier construction
    1.2 Risk–return trade-off visualization
    1.3 Portfolio optimization using convex methods

Comparison of GMV, MSR, and custom utility portfolios

2. Features Implementation
   
    2.1 Efficient Frontier
    2.2 Computes portfolio return–volatility combinations
    2.3 Visualizes feasible region vs efficient set

3. Supports multiple assets

    3.1 Global Minimum Variance (GMV) Portfolio: Lowest possible portfolio risk
    3.2 Maximum Sharpe Ratio (MSR) Portfolio: Optimal weights for highest risk-adjusted return (Allows specifying custom risk-free rate)
