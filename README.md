# Comparing-Model-with-SimpleRNN-and-Bidirectional-LSTM-
Here we are Comparing Model with SimpleRNN and Bidirectional LSTM on Time Series Data having Trend and Seasonality

The goal is to understand ideally using only one particular one in the model which one is better at predicting a time series data with trend and seasonality.

Conclusion :
SimpleRNN with 64 is used to fit the series with trend and seasonality better than with Bidirectional LSTM with 32 (since Bidirectional overall is 32*2 = 64 ) 
The sudden peak is better predicted in the SimpleRNN network
