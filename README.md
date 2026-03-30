# CPPI and OBPI under Diffusion and Jump Models

This project studies portfolio insurance strategies through a quantitative comparison between Constant Proportion Portfolio Insurance (CPPI) and Option-Based Portfolio Insurance (OBPI).

The analysis is based on Monte Carlo simulations under two market settings: a continuous diffusion model (GBM / Black–Scholes dynamics) and a Merton jump-diffusion model. The project examines terminal wealth distributions, shortfall probability, tail-risk measures, the impact of the CPPI multiplier and rebalancing frequency, as well as the effect of a leverage cap.

A benchmark comparison with OBPI is also provided in order to contrast dynamic portfolio insurance with an option-based strategy offering a hard floor at maturity.

## Project content

- Definition and implementation of a discrete-time CPPI strategy
- Comparison between diffusion dynamics and jump-diffusion dynamics
- Analysis of shortfall probability and shortfall severity
- Study of the effect of the CPPI multiplier and monitoring frequency
- Leverage-cap variant to control tail risk
- Benchmark comparison with OBPI

## Main ideas

The project highlights a strong contrast between the two modelling frameworks.

Under GBM dynamics, shortfall risk mainly comes from discrete rebalancing and remains negligible when monitoring is frequent. Under the Merton jump-diffusion model, CPPI becomes much more exposed to gap risk, and increasing the rebalancing frequency is no longer sufficient to eliminate floor breaches.

The results also show that leverage materially increases tail risk, while a leverage cap improves downside protection at the cost of reduced upside participation. OBPI, by construction, preserves a hard floor at maturity.

## Methods and tools

* Python
* Jupyter Notebook
* Monte Carlo simulation
* GBM / Black–Scholes dynamics
* Merton jump-diffusion model
* Quantitative risk analysis

