# AVOCADO MARKET PREDICTION

The objective of this case study is to predict the price of avocado sold in the US using historical dataset. Data represents weekly 2018 retail scan data for National retail volume (units) and price. 

## What is Facebook Prophet?

Prophet is open source software released by Facebook’s Core Data Science team. Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. Prophet works best with time series that have strong seasonal effects and several seasons of historical data. For more information, please check this out:

* [Prophet forecasting at scale](https://research.fb.com/prophet-forecasting-at-scale/)
* [Quick start to Prophet](https://facebook.github.io/prophet/docs/quick_start.html)

Prophet implements an additive regression model with four elements:

* A piecewise linear, Prophet automatically picks up change points in the data and identifies any change in trends. 
* A yearly seasonal component modeled using Fourier series.
* A weekly seasonal component.
* A holiday list that can be manually provided.

Additive Regression model takes the form: 
$$
Y=β_0+∑^p_{_j=1} f_j(X_j )+ϵ
$$




**NOTE:**

* You must install fbprophet package as follows: 

```python
pip install fbprophet
```

* If you encounter an error, try: 

```python
conda install -c conda-forge fbprophet
```
