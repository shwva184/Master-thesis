# Multi-horizon forecasting of power demand for gas turbine in energy industry


Abstract
Multi-horizon forecasting of power demand in gas turbines is desired for efficient business
decision-making in the energy industry. Having a separate model for each horizon
leads to the increase in the number of models as the number of horizons of interest increases.
This increasing number of models translates to additional training, maintenance,
and computational costs. The aim of this thesis is to perform multi-horizon forecasting
of the power demand of a gas turbine using a single forecasting framework. The empirical
work of this thesis was carried out in co-operation with an energy company based in
Sweden. The dataset used for the empirical study contains power demand or active load
recorded every minute by gas turbine sensor in an energy industry from February 2021 to
February 2022. These data have been aggregated from minute to hourly frequency by taking
the average of power demand for each hour. 24 hours (steps) ahead, 72 hours (steps)
ahead and 168 hours (steps) ahead are considered as the 3 horizons of interest.
5 experiments were carried out to achieve this aim. For the first experiment, Seasonal
Autoregressive Integrated Moving Average (SARIMA) model was used. In the second,
third and fourth experiments the eXtreme Gradient Boosting (XGBoost) model was recursively
used with a direct strategy to obtain 24 steps, 72 steps and 168 steps forecast respectively.
Lastly, the Neural Hierarchical Interpolation for Time Series forecasting (N-Hits)
model was used in the fifth experiment. The results obtained in terms of losses (Root Mean
Square Error (RMSE), Mean Absolute Error (MAE) and Mean Absolute Percentage Error
(MAPE)) and residuals suggest that N-HiTS performed better than all other 4 experiments
conducted.
