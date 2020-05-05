# LSTM Neural Network for Time Series Prediction

LSTM built using the Keras Python package to predict time series steps and sequences. Includes sine wave and stock market data.

*Note:* **The prebuilt version of Tensorflow pulled in with pip will not run on
older Mac OSX machines. Prebuilt Tensorflow requires CPUs that have AVX
instruction set. You can find out if your Mac support it using the command
`sysctl -a | grep machdep.cpu.features` If it doesn't, it is recommended to build
Tensorflow from source. Follow the instructions at
https://www.tensorflow.org/install/source**

[Full article write-up for this code](https://www.altumintelligence.com/articles/a/Time-Series-Prediction-Using-LSTM-Deep-Neural-Networks)

[Video on the workings and usage of LSTMs and run-through of this code](https://www.youtube.com/watch?v=2np77NOdnwk)

## Requirements

Install requirements.txt file to make sure correct versions of libraries are being used.

* Python 3.5.x
* TensorFlow 1.10.0
* Numpy 1.15.0
* Keras 2.2.2
* Matplotlib 2.2.2

Output for sine wave sequential prediction:

![Output for sin wave sequential prediction](https://www.altumintelligence.com/assets/time-series-prediction-using-lstm-deep-neural-networks/sinwave_full_seq.png)

Output for stock market multi-dimensional multi-sequential predictions:

![Output for stock market multiple sequential predictions](https://www.altumintelligence.com/assets/time-series-prediction-using-lstm-deep-neural-networks/sp500_multi_2d.png)
