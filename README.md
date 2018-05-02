# Bitcoin-Prediction
Bitcoin Prediction with Long Short-Term Memory Neural Network architecure, Facebook's Prophet package and ARIMA model. Experiment's results are showed with different test sizes such as 7 days, 15 days, 30 days and 60 days.

## Error comparison : sMAPE
sMAPE refers to Symmetric Mean Absolute Percentage Error: 
![alt text](https://github.com/namlih/Bitcoin-Prediction/blob/master/smape.png "sMAPE")

|  Test Sizes | LSTM  | ARIMA | Prophet |
| :---------: | :---: | :---: | :-----: |
| **7 days**  | 11.78 |  3.71 |  32.79  |
| **15 days** | 13.26 |  4.51 |  37.30  |
| **30 days** |  9.55 |  4.21 |  24.29  |
| **60 days** | 14.10 |  4.65 |  32.84  |

## Error comparison : RMSE
RMSE refers to Root Mean Square Error: 
![alt text](https://github.com/namlih/Bitcoin-Prediction/blob/master/rms.png "RMSE")

|  Test Sizes | LSTM  | ARIMA | Prophet |
| :---------: | :---: | :---: | :-----: |
| **7 days**  | 1086  |  426  |  2594   |
| **15 days** | 1250  |  427  |  2891   |
| **30 days** |  965  |  430  |  2235   |
| **60 days** | 1492  |  458  |  2797   |

## Time comparison in seconds

|  Test Sizes | LSTM  | ARIMA | Prophet |
| :---------: | :---: | :---: | :-----: |
| **7 days**  |  956  |  564  |  0.21   |
| **15 days** |  825  |  1133 |  0.23   |
| **30 days** |  982  |  2171 |  0.14   |
| **60 days** |  769  |  4718 |  0.26   |

