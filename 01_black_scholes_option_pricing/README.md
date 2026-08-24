# Black–Scholes Option Pricing

## Overview

This project implements the Black–Scholes model for pricing European call and put options. The aim is to build a strong foundation in quantitative finance by connecting mathematical concepts with practical computational implementation.

The project will begin with a basic implementation of the Black–Scholes pricing equations and will gradually be extended to explore option Greeks, implied volatility, numerical methods, and comparisons with alternative pricing approaches.

### Objectives:-

1. Understand the mathematical foundations of the Black–Scholes model.
2. Implement the pricing equations from scratch in Python.
3. Calculate European call and put option prices.
4. Study the effect of model parameters on option prices.
5. Validate the implementation against known results.
6. Gradually extend the project toward more advanced quantitative-finance methods.


#### Mathematical Model

    For a European call option, the Black–Scholes price is given by
    
    [
    C = S_0N(d_1) - Ke^{-rT}N(d_2)
    ]
    
    and for a European put option,
    
    [
    P = Ke^{-rT}N(-d_2) - S_0N(-d_1)
    ]
    
    where
    
    [
    d_1 =
    \frac{
    \ln(S_0/K) + \left(r+\frac{1}{2}\sigma^2\right)T
    }{
    \sigma\sqrt{T}
    }
    ]
    
    and
    
    [
    d_2 = d_1-\sigma\sqrt{T}.
    ]
    
    Here, (S_0) is the current underlying asset price, (K) is the strike price, (T) is the time to expiration, (r) is the risk-free interest rate, and (\sigma) is the volatility of the underlying asset.
    
     Project Status
    
    Current stage: Initial implementation
    
    This project will be developed incrementally, with each stage documented through the repository's commit history.
