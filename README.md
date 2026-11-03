# Derivatives Pricing & Hedging Lab

Status: Building. This repository currently contains the project roadmap and Python ignore rules. Pricing models, hedging simulations, tests, and benchmarks are planned and have not yet been implemented.

Building:
- Monte Carlo pricing for European and Asian options.
- Greeks with Black–Scholes validation.
- Variance reduction using antithetic sampling and control variates.
- Discrete delta-hedging simulations with transaction costs and volatility misspecification.
- Planned extension: Longstaff–Schwartz pricing for American options with a binomial benchmark.
- Reproducible experiments, tests, and accuracy/runtime comparisons.

## Planned development sequence

1. Implement Black–Scholes prices and Greeks with reference checks.
2. Add Monte Carlo estimators, confidence intervals, convergence experiments, and variance reduction.
3. Add discrete delta hedging and evaluate hedging error, transaction costs, and model misspecification.
4. Extend to American options using Longstaff–Schwartz and a binomial benchmark.
5. Document assumptions, limitations, reproducible commands, and measured results as they are built.
