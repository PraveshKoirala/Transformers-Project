# Transformers-Project
Transit Delay Time prediction using Time Series Transformers. Parts of the code are based on https://github.com/tdjuly/TimeSeriesTransformer

## Problem Statement
In fixed line transit system, it is desirable to not be delayed at all. Since it's not alwayspossible to do so, the next desirable thing would be to accurately forecast the amount of delayso that it may be communicated to the customers. This project is centered around creating one suchmodel that takes in predictors like weather, temperature, school break information, holidays, humidity,etc. and predicts an expected delay for a given route segment for a given time of the day.

Time series transformers are Encoder Decoder transformers that work with continuous time time series predictors. In this project, we not only use the Time Series Transformer but also extend it such that it works with a mix of categorical and continuous predictors.

## Base Paper
This project is largely based on the paper "Deep Transformers Model for Time Series Forecasting: An Influenza Case". The details about the paper and an in-depth analysis can be found at https://github.com/PraveshKoirala/Transformers-Paper.

## HuggingFace Spaces
The huggingface spaces link for this project is: https://huggingface.co/spaces/praveshkoirala/delay-prediction

## References and Resource Links
- [Lu, F. S., Hattab, M. W., Clemente, C. L., Biggerstaff, M.,
and Santillana, M. Improved state-level influenza now casting in the united states leveraging internet-based data
and network approaches. Nature Communications, 10(1):
147, 2019. ISSN 2041-1723](https://www.nature.com/articles/s41467-018-08082-0/)
- [Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones,
L., Gomez, A. N., Kaiser, L. u., and Polosukhin, I. Attention is all you need. In Guyon, I., Luxburg, U. V., Bengio, S., Wallach, H., Fergus, R., Vishwanathan, S., and
Garnett, R. (eds.), Advances in Neural Information Processing Systems 30, pp. 5998–6008. Curran Associates,
Inc., 2017.](https://arxiv.org/abs/1706.03762)
- [Wen, Q., Zhou, T., Zhang, C., Chen, W., Ma, Z., Yan, J., & Sun, L. (2022). Transformers in time series: A survey. arXiv preprint arXiv:2202.07125.](https://arxiv.org/abs/2202.07125)
- [Zeng, A., Chen, M., Zhang, L., & Xu, Q. (2022). Are Transformers Effective for Time Series Forecasting?. arXiv preprint arXiv:2205.13504.](https://arxiv.org/abs/2205.13504v1)
- [Cai, Ling, et al. "Traffic transformer: Capturing the continuity and periodicity of time series for traffic forecasting." Transactions in GIS 24.3 (2020): 736-755.](https://www.bibsonomy.org/bibtex/0f2bf4e080a39cbe70f099c0de9b0c5f#:~:text=Traffic%20transformer%3A%20Capturing%20the%20continuity%20and%20periodicity%20of,of%20jointly%20modeling%20spatio-temporal%20dependencies%20at%20different%20scales.)
- [Xu, Mingxing, et al. "Spatial-temporal transformer networks for traffic flow forecasting." arXiv preprint arXiv:2001.02908 (2020).](https://arxiv.org/abs/2001.02908)

## Video
TBD

## Resources
- [Cdc fluview dashboard.](https://gis.cdc.gov/grasp/fluview/fluportaldashboard.html)
- [Time Series in Python — Exponential Smoothing and ARIMA processes](https://towardsdatascience.com/time-series-in-python-exponential-smoothing-and-arima-processes-2c67f2a52788)
- [Pearson's Correlation](https://en.wikipedia.org/wiki/Pearson_correlation_coefficient)
- [Time Series Transformer implementation](https://github.com/tdjuly/TimeSeriesTransformer)
- [Graph Neural Networks](https://www.sciencedirect.com/science/article/pii/S2666651021000012)

