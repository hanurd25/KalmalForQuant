# KalmalForQuant
Kalman filter for quantitative analysis.

## Background
Kalman filters can be ideal for pairs trading or trend-following.


Noisy stock prices can obscure true trends. The Kalman filter recovers the underlying state via two steps:
- **Prediction**: Uses a dynamic model to forecast the next state (e.g., price velocity).
- **Update**: Blends prediction with noisy measurements using optimal weights based on uncertainties.

Unlike moving averages, it adapts in real-time without fixed windows.
[Learn more](https://medium.com/intro-to-artificial-intelligence/kalman-filter-in-stock-trading-552e1e4b2dfb).


### Coding in ![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)

### Sources
https://julia.quantecon.org/introduction_dynamics/kalman.html
https://www.quantanalysis.org.uk/python/kalman-filter/
https://www.youtube.com/watch?v=zVJY_oaVh-0
https://www.cis.upenn.edu/~mkearns/finread/filtering_in_finance.pdf


