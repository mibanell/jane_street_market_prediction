# Jane Street Market Prediction

In this repository you can see my model developed for the Kaggle Competition [Jane Street Market Prediction](https://www.kaggle.com/c/jane-street-market-prediction).

The submitted model is a neural network with the following key aspects:
  * The 130 features are anonymized so that its meanings are unknown.
  * Based on the EDA and the tagset, I assumed that there are groups of 5 features that measure the same metric over different timeframes.
  * There is a custom preprocessing layer to add a 3rd axis for the 5 timeframes.
  * There is a LSTM layer applied over each group of temporal features so that each group is encoded into one single feature.
  * The next layers use a ResNet architecture for 3 (dense->swish activ.->dropout) modules.

## Author

<br>
<p align="center">
  <a href="https://github.com/mibanell">
    <img  src="img/signature.png" width="100">
  </a>
</p>
<p align="center">
    <a href="https://github.com/mibanell">Miguel Ángel Ballester Granell</a>
    <br>
    <a href="https://www.linkedin.com/in/miguelangelballestergranell/">LinkedIn</a>
</p>
