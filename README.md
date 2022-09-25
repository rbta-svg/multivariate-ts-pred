# multivariate-ts-pred
The goal of this project is the prediction of future samples in a multivariate time series. The predictions were only made for 3 fourths of the final test set, since phase 2 never happened due to technical problems.


The features associated with the input/output tensors are the following: 
Sponginess, Wonder Level, Crunchiness, Loudness on Impact, Soap Slipperiness and Hype Root. 

![https://imgur.com/a9cxlXY](Features)

Clearly, those features hide the real world event behind the data, so supporting the model research through ex- ploratory data analysis was quite limited. Instead of using scientific research to find models that best fit a certain real world task resolution, we looked for more general neural network architectures and experimented a lot through trial and error.

The best model involved the usage of a Bi-Directional LSTM, leading to a final RMSE of 3.96
Below some of the metrics: 


![https://imgur.com/8CJKJHA](Metrics)
