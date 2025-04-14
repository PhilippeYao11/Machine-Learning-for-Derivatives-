# 📘 Machine Learning and Derivatives Pricing

This repository contains a set of **mini-projects** demonstrating the application of **neural networks** and **stochastic optimization** techniques to the **pricing and hedging of financial derivatives**. It is designed with a practical and educational focus, using simulated financial data.

---

## 💼 Financial Applications

### 🟦 Pricing American and Bermudan Options

We tackle the challenging problem of **optimal stopping** for American and Bermudan options:
- **Snell envelope** framework to model the optimal exercise strategy,
- **Longstaff-Schwartz algorithm** using **Monte Carlo regression**,
- **Deep Optimal Stopping** (Becker et al., 2019): using neural networks to learn the optimal stopping rule,
- **Dual approach** (Rogers, 2002): computation of upper bounds via martingale optimization,
- **Confidence interval construction** and **point estimates**.

### 🟨 Hedging European Options

We also explore the **hedging of European options**:
- **Delta-neutral hedging**,
- **Mean-quadratic hedging**, minimizing the quadratic error between portfolio value and final payoff.


## 📚 References

- Becker, Cheridito, Jentzen (2019), *Deep Optimal Stopping*.
- Rogers (2002), *Monte Carlo valuation of American options via primal-dual simulation*.


