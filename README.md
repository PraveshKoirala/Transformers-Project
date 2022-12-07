# Transformers-Project
Transit Delay Time prediction using Time Series Transformers

## Problem Statement
In fixed line transit system, it is desirable to not be delayed at all. Since it's not alwayspossible to do so, the next desirable thing would be to accurately forecast the amount of delayso that it may be communicated to the customers. This project is centered around creating one suchmodel that takes in predictors like weather, temperature, school break information, holidays, humidity,etc. and predicts an expected delay for a given route segment for a given time of the day.

Time series transformers are Encoder Decoder transformers that work with continuous time time series predictors. In this project, we not only use the Time Series Transformer but also extend it such that it works with a mix of categorical and continuous predictors.

## References
This project is largely based on the paper "Deep Transformers Model for Time Series Forecasting: An Influenza Case". The details about the paper and an in-depth analysis can be found at https://github.com/PraveshKoirala/Transformers-Paper.

## HuggingFace Spaces
The huggingface spaces link for this project is: https://huggingface.co/spaces/praveshkoirala/delay-prediction

