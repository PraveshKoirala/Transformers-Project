# Transformers-Project
Transit Delay Time prediction using Time Series Transformers

## Problem Statement
In fixed line transit system, it is desirable to not be delayed at all. Since it's not alwayspossible to do so, the next desirable thing would be to accurately forecast the amount of delayso that it may be communicated to the customers. This project is centered around creating one suchmodel that takes in predictors like weather, temperature, school break information, holidays, humidity,etc. and predicts an expected delay for a given route segment for a given time of the day.

Time series transformers are Encoder Decoder transformers that work with continuous time time series predictors. In this project, we not only use the Time Series Transformer but also extend it such that it works with a mix of categorical and continuous predictors.

## References
This project is largely based on the paper "Deep Transformers Model for Time Series Forecasting: An Influenza Case". The details about the paper and an in-depth analysis can be found at https://github.com/PraveshKoirala/Transformers-Paper.

## HuggingFace Spaces
The huggingface spaces link for this project is: https://huggingface.co/spaces/praveshkoirala/delay-prediction

## References
- Lu, F. S., Hattab, M. W., Clemente, C. L., Biggerstaff, M.,
and Santillana, M. Improved state-level influenza now casting in the united states leveraging internet-based data
and network approaches. Nature Communications, 10(1):
147, 2019. ISSN 2041-1723
- Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones,
L., Gomez, A. N., Kaiser, L. u., and Polosukhin, I. Attention is all you need. In Guyon, I., Luxburg, U. V., Bengio, S., Wallach, H., Fergus, R., Vishwanathan, S., and
Garnett, R. (eds.), Advances in Neural Information Processing Systems 30, pp. 5998–6008. Curran Associates,
Inc., 2017.
- Wen, Q., Zhou, T., Zhang, C., Chen, W., Ma, Z., Yan, J., & Sun, L. (2022). Transformers in time series: A survey. arXiv preprint arXiv:2202.07125.
- Zeng, A., Chen, M., Zhang, L., & Xu, Q. (2022). Are Transformers Effective for Time Series Forecasting?. arXiv preprint arXiv:2205.13504.

## Resources
- [Cdc fluview dashboard.](https://gis.cdc.gov/grasp/fluview/fluportaldashboard.html)
- [Time Series in Python — Exponential Smoothing and ARIMA processes](https://towardsdatascience.com/time-series-in-python-exponential-smoothing-and-arima-processes-2c67f2a52788)
- [Pearson's Correlation](https://en.wikipedia.org/wiki/Pearson_correlation_coefficient)
- [Time Series Transformer implementation](https://github.com/tdjuly/TimeSeriesTransformer)
