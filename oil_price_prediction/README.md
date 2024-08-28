In this project, I teamed up with fellow students to explore how oil futures prices change over time and what drives these shifts.
We took a few different approaches to dig into the data.

First, we simply looked at the prices over time and saw that the biggest jumps in oil futures usually happened during major social and economic events—like the Great Recession, the COVID-19 pandemic, and Russia's invasion of Ukraine in 2022.

On the statistical side, we experimented with a variety of models.
I focused mainly on [ARIMA](https://www.investopedia.com/terms/a/autoregressive-integrated-moving-average-arima.asp) and [Hidden Markov Models](https://en.wikipedia.org/wiki/Hidden_Markov_model) (HMMs).
It didn’t take long to realize that ARIMA was too simple for this kind of data since it assumes patterns that hold up over long periods, which just isn’t the case with stock prices.

HMMs, on the other hand, showed some real promise.
While most advice suggests only predicting stock prices up to 6 months out, I found that by training an HMM on past data, I could make accurate predictions even 2 years beyond the end of the training period.

Overall, our team found that HMMs could be a strong tool for projecting long-term investments like oil futures. Future projects could focus on testing the durability of this model and refining our approach.
