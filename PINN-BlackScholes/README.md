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

## Black-Scholes Closed-Form Solution

The Black-Scholes formula provides the theoretical price of European-style options.

### Call Option Price
$$
C(S, t) = S \cdot N(d_1) - K e^{-r(T - t)} \cdot N(d_2)
$$



Where:
$$
d_1 = \frac{\ln\left(\frac{S}{K}\right) + \left(r + \frac{\sigma^2}{2}\right)(T - t)}{\sigma \sqrt{T - t}}
$$
$$
d_2 = d_1 - \sigma \sqrt{T - t}
$$

### 📘 Variables

| Symbol | Meaning |
|--------|---------|
| \( S \) | Current stock price |
| \( K \) | Strike price of the option |
| \( T \) | Expiration time (in years) |
| \( t \) | Current time |
| \( r \) | Risk-free interest rate (annualized) |
| \( \sigma \) | Volatility of the stock (standard deviation of returns) |
| \( N(\cdot) \) | Cumulative distribution function of the standard normal distribution |
