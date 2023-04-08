# Option-Volatility-Pricing-and-Forecast
Uses GARCH to forecast Option Volatility and inputs that to Black Scholes Model, thus comparing the volatility spread between market calls and theoretically derived values.

Recently, I came across some interesting financial models and decided to apply them to the Tesla stock data fetched from Yahoo Finance.

1. Firstly, I used the #GARCH model on the stock data to forecast the volatility for the next year. GARCH, or Generalized Autoregressive Conditional Heteroskedasticity, is a statistical model that is used to analyze and forecast the volatility of financial assets. With the help of this model, I was able to predict the volatility for #Tesla stock for the next year, which I then used as input to the Black Scholes Merton model.

2. Black Scholes Merton's (BSM) model is a mathematical model used for pricing options contracts. Using the forecasted volatility as an input, I compared the theoretical call price to the ones trading in the market, and to my surprise, the theoretical price was sitting on top.

3. Next, I came across the #Prophet model (tried #ARIMA but didn't do so well as we have Stationarity assumption, Parameter estimation, and Inability to capture seasonality), which gave me a 90% confidence interval of my data. Prophet is a forecasting model that is specifically designed for time-series data. With the help of this model, I was able to make predictions about Tesla stock prices for the future.

Let's ignite a thought-provoking conversation with some open-ended questions:

Have you ever thought about how different results could have been obtained if the GARCH (or some other) model predicted different volatility for a particular stock? Could we trade VIX based on the difference we observe? Once you test a hypothesis in the market, how do you increase the confidence to take a position based on that belief?
Moreover, I noticed that the outcomes change a lot based on some parameter changes and assumptions. How reliable are these models, and what are the possible limitations? Do models #replicate the markets' or do they #influence the markets and to what level? It's fascinating how models can interact with the market, and the play between the #P measure and #Q measure never fails to amaze me.

I welcome your feedback and ideas on these projects, and I had fun working on them. Feel free to message me for the raw codes or files, and stay tuned for my upcoming work on #MLE (Maximum Likelihood Estimator) and #MeanVariance optimization. Check out the attached #PDF for the complete details. Thank you for reading, and I'm excited to hear from you!

PS: You just need to change the ticker symbol and can play around with any other stock you like.
