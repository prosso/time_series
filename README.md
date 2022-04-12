
# time_series

Time-series forecasting models are the models that are capable to predict future values based on previously observed values.


# Scaling the input
We need to scale the input data, and we choose a range between -1 and 1. Note that large input values (e.g. a spread of hundreds or thousands of units) can result in a model that learns large weight values. A model with large weight values is often unstable, meaning that it may suffer from poor performance during learning and sensitivity to input values resulting in higher generalization error. You can also choose the range [0, 1] Next we need to split the data into train and test, and feed it into the RNN. 

Two RNN are defined, LSTM and GRU respectively. 
