# econ3916-lab05-monte-carlo
# Monte Carlo Engine -- Probability & Simulation

## Objective

Apply probability theory and Monte Carlo simulation to analyze convergence, conditional probability, Bayesian inference, and financial risk through practical economic and statistical applications.

## Methodology

- Simulated 10,000 fair coin flips and tracked the running proportion of heads to visualize the Law of Large Numbers and convergence toward the theoretical probability of 0.50.
- Simulated 10,000 Monty Hall games to compare always staying versus always switching and demonstrate how conditional probability affects decision-making.
- Applied Bayes' Theorem to a disease screening problem using a 95% sensitivity, 90% specificity, and 1% disease prevalence.
- Simulated 100,000 individuals to compare theoretical Bayesian probabilities with observed screening outcomes and demonstrate the base rate fallacy.
- Generated simulated daily portfolio returns and used Monte Carlo methods to estimate 95% and 99% Value at Risk (VaR) and Expected Shortfall (ES) for a 1,000,000 dollar equity portfolio.
- Examined how Monte Carlo estimates become more stable as the number of simulations increases and verified the expected O(1/sqrt(n)) convergence rate using pi estimation.
- Used an interactive simulation dashboard to test how sample size, disease prevalence, expected return, volatility, and portfolio value affect estimated outcomes.

## Key Findings

- The coin-flip simulation demonstrated the Law of Large Numbers, with the sample proportion moving closer to the theoretical probability of 0.50 as the number of observations increased.
- In the Monty Hall simulation, switching won 66.94% of games compared with 33.06% when staying, closely matching the theoretical 2/3 versus 1/3 probabilities.
- Despite the disease test having 95% sensitivity, Bayes' Theorem gave only about an 8.8% probability of actually having the disease after a positive result when prevalence was 1%. The simulation produced a similar result of about 9.2%.
- Increasing disease prevalence from 1% to 10% increased the probability of actually being sick after a positive result to approximately 51.4%, demonstrating the importance of base rates when interpreting test results.
- For the 1,000,000 dollar portfolio, the simulation produced a 95% VaR of 19,494 dollars and a 95% Expected Shortfall of 24,230 dollars.
- The 99% VaR increased to 27,046 dollars, while the 99% Expected Shortfall increased to 31,221 dollars, showing how potential losses become more severe deeper in the tail of the distribution.
- Expected Shortfall provided additional information beyond VaR by measuring the average severity of losses once returns entered the worst tail of the distribution.
- Overall, the lab demonstrated how simulation can connect theoretical probability concepts to practical problems in economics, decision-making, Bayesian inference, and financial risk management.
