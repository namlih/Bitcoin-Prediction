# Bitcoin-Prediction
Bitcoin Prediction with Long Short-Term Memory Neural Network architecure, Facebook's Prophet package and ARIMA model. Examples are showed with different test sizes such as 7 days, 15 days and 30 days.

## Error comparison 1 : sMAPE
sMAPE refers to Symmetric Mean Absolute Percentage Error: 
![alt text](https://github.com/namlih/Bitcoin-Prediction/blob/master/smape.png "sMAPE")

|  Test Sizes | LSTM  | ARIMA | Prophet |
| :---------: | :---: | :---: | :-----: |
| **7 days**  | 11.78 |  3.71 |  32.79  |
| **15 days** | 13.26 |  4.51 |  37.30  |
| **30 days** |  9.55 |  4.21 |  24.29  |
