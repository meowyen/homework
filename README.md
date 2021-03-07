# Unit 14 - Deep Learning

## Analysis

- [LSTM Stock Predictor using Fear and Greed Index](lstm_stock_predictor_fng.ipynb)
- [LSTM Stock Predictor using Closing Prices](lstm_stock_predictor_closing.ipynb)
- [Datasets](Data)

### Which model has a lower loss?

The closing prices model has a lower loss (0.01309 vs 0.0849) than this model.

### Which model tracks the actual values better over time?

This closing prices model tracks the actual values better over time than this model.

### Which window size works best for the model?

The window size of 1 yielded the lowest loss for both models. The difference was negligible for the closing prices model. The difference for the fear and greed index model was around 7% less.