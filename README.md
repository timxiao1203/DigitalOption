# Digital Option

This article presents a pricing model for skewed European interest rate digital option. The traditional pricing model is under the Black-Scholes framework. The new skew-adjusted model replicates a digital option by a portfolio of vanilla call options, and/or zero-coupon bonds and/or floating rate notes (FRNs) https://finpricing.com/lib/FiBond.html. The new model provides a better approach to pricing skewed European interest rate digital options.

There are four types of digital options and the responding matured payoffs are as follows: Digital Call (Cash or Nothing), Digital Put (Cash or Nothing), Digital Call (Asset or Nothing), and Digital Put (Asset or Nothing) where I is indicator function; T is the Maturity of option; f t  is the Underlying interest rate at time t; K is the Strike; σ(K) is the Volatility function in terms of K.

For all those types of options, close-form solutions of prices are provided. The initial prices at t = 0 of the four digital options can be given where df( , ) is the discount function and

One may see that a skew-adjusted digital option can be approximately evaluated by a portfolio of vanilla call options, and/or zero-coupon bonds and/or FRNs. There are three ways to use this model:

We find that the results are very sensitive to the method used for discretizing ∂σ/∂K. This is because the volatility surface is not so smooth. We suggest that method 2 should be used for the calculations.

