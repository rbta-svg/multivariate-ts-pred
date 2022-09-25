# multivariate-ts-pred
The goal of this project is the prediction of future samples in a multivariate time series. The predictions were only made for 3 fourths of the final test set, since phase 2 never happened due to technical problems.


The features associated with the input/output tensors are the following: 
Sponginess, Wonder Level, Crunchiness, Loudness on Impact, Soap Slipperiness and Hype Root. 


<img width="464" alt="Screenshot 2022-09-25 at 18 40 47" src="https://user-images.githubusercontent.com/57828824/192155217-278a4625-0173-4f88-8e7d-0c4b2f31e63b.png">

Clearly, those features hide the real world event behind the data, so supporting the model research through ex- ploratory data analysis was quite limited. Instead of using scientific research to find models that best fit a certain real world task resolution, we looked for more general neural network architectures and experimented a lot through trial and error.

The best model involved the usage of a Bi-Directional LSTM, leading to a final RMSE of 3.96
Below some of the metrics: 

<img width="586" alt="Screenshot 2022-09-25 at 18 41 00" src="https://user-images.githubusercontent.com/57828824/192155234-349a18b4-fdb7-479b-8234-b0fb8dad126d.png">



