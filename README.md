# Bachelors Thesis: Stochastic Differential Equations in Finance

##  Project Overview

This repository contains the work of my Bachelor's thesis, which explores the use of **stochastic differential equations (SDEs)** in **financial mathematics**. The central focus of this study is the derivation and application of the **Black-Scholes formula** for option pricing, along with its theoretical foundations and practical implementation.

---

##  Topics Covered

- **Algebraic Structures and Probability Spaces**
- **Conditional Probability, Expectation, and Convergence**
- **Stochastic Processes, Martingales, and Brownian Motion**
- **Itô Integral and Stochastic Differential Equations**
- **Derivation and Mathematical Justification of the Black-Scholes Formula**
- **Solution via Heat Equation and Fourier Transform**
- **Computational Implementation and Market Data Application**
- **Volatility and Interest Rate Estimation from Real Data**
- **Computational Implementation and Market Data Application**
- **Comparison of Theoretical Prices vs. Real Option Prices**
- **Translation of the Thesis using Physics Informed Neural Networks (PINN's) (in progress)**
---

##  Methodology

1. **Mathematical Foundation**:  
   Developed a rigorous understanding of stochastic processes and Itô calculus to model asset price dynamics as **Geometric Brownian Motion (GBM)**.

2. **Black-Scholes Derivation**:  
   Derived the **Black-Scholes Partial Differential Equation (PDE)** for European call and put options.

3. **Analytical Solution**:  
   Transformed the Black-Scholes PDE into the **heat equation** and solved it using the **Fourier transform**.

4. **Empirical Application**:  
   Used real market data from **Yahoo Finance** to price options and compare theoretical vs. actual outcomes.

---

##  Real-World Case Study

A case study was conducted using historical stock prices from Yahoo Finance to validate the Black-Scholes model. Results were analyzed to evaluate the model's performance in real-world financial markets.

---

##  Ongoing Work

Currently, I am extending this work using **PINN** to translate and enhance the original thesis.

---

##  Files

- `Original_Thesis` — My original thesis written in Spanish and the source code (no AI)
- `PINN-BlackScholes` — Contains the code of using PINN in solving the Black Scholes partial differential equation
- `solution.pdf`- Contains the english translation of the solution of the PDE 

---

##  Future Work

- Full translation of the thesis into English
- Implementation of RL agents for option pricing
- Comparison between analytical Black-Scholes results and RL-based results

---

##  Contact

**Ricardo Alonso Manjarrez Retes**  
Graduate Student, Computer Science  
Email: ramr99@nmsu.edu  

---

##  License

This project is under the MIT License. See `LICENSE` for more details.

