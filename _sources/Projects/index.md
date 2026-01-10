# Projects

---

![Distributions of observed and generated precipitation and temperature](../_static/images/swxg.svg){width=50%}

###### [`swxg`](https://github.com/xthames/swxg)
`swxg` is a Python library for generalized multivariate, multisite, copula-based stochastic weather generation. It addresses the challenge of generating realistic, spatially- and temporally-correlated precipitation and temperature data for water resources planning and climate vulnerability assessments. The library uses semiparametric fitting for precipitation via Gaussian mixture hidden Markov models, followed by conditional copula-based temperature generation. `swxg` includes comprehensive validation tools to assess goodness of fit and ensure generated weather is statistically indistinguishable from observations. The software is openly available on GitHub under an MIT license and is designed for flexible integration into exploratory modeling frameworks, making it suitable for diverse hydroclimatic applications requiring synthetic weather data across multiple sites.

---

![Workflow for better localized NWS predictions with an ANN](../_static/images/wxfcst.png)

###### [`wxfcst`](https://github.com/xthames/wxfcst)
Accurate sub-grid weather forecasting remains a critical challenge, particularly with local applications where discrepancies in precipitation and temperature forecasts can exacerbate issues related to water resource management. Numerical weather prediction models, like the National Weather Service's High-Resolution Rapid Refresh, offer precision at regional scales but struggle to resolve sub-grid spatial variability. To address this, a regression-based artificial neural network that links forecasts to observations from a personal weather station was constructed. The artificial neural network achieved an R^2^ of 0.951, leading to substantially improved forecasting skill in the predicted precipitation and slightly improved skill in the predicted temperature when compared to the raw forecast. The artificial neural network shows highest skill at longer lead times for precipitation and shorter lead times for temperature. While a small number of precipitation samples and possible model overfitting warrant further investigation, this methodology is shown to be accessible, computationally efficient, and scalable, offering significant potential for local weather forecasting applications.

---
