# Physics-Informed Neural Network (PINN) for Black-Scholes PDE

This repository implements a **Physics-Informed Neural Network (PINN)** for solving the Black-Scholes equation:

The Black-Scholes equation is given by:

$$
\frac{\partial V}{\partial t} + \frac{1}{2} \sigma^2 S^2 \frac{\partial^2 V}{\partial S^2} + rS \frac{\partial V}{\partial S} - rV = 0
$$

Where:
- $V(t, S)$ is the option price at time $t$ and asset price $S$.
- $r$ is the risk-free interest rate.
- $\sigma$ is the volatility of the underlying asset.
- $S$ is the asset price.
- $t$ is the time.

### Initial/Boundary Conditions

The boundary condition for a European call option at maturity ($t = T$) is:

$$
V(T, S) = \max(S - K, 0)
$$

Where $K$ is the strike price.
