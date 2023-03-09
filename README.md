# Text classification

## Problem Statement

Text classification is an important process. In this scenario, we classify texts, then predict its type. Types include tech, sport, politics, entertainment, and business 

## Model

### RNN:
A recurrent neural network is needed as it allows time-series context to flow through the network. RNNs take in sequences of text as inputs and return the type of the text as output; many-to-one.

![RNN](https://user-images.githubusercontent.com/62629426/222014075-63851463-0c0e-4ad9-9d37-44d530699082.png)

Each rectangle is a vector and arrows represent functions, the green vectors hold the RNN’s state

### Libraries: 
- [Tensorflow - Keras](https://www.tensorflow.org/api_docs/python/tf/keras)
- [tensorflow](https://www.tensorflow.org/)
- [Numpy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/))
- [nltk](https://www.nltk.org/)
- [Matplotlib](https://matplotlib.org/)
- [csv](https://docs.python.org/3/library/csv.html)

### Results:
Type of text; one of the following

`business`, `entertainment`, `politics`, `sport`, `tech`

### Accuracy:
- loss: 0.4184 
- accuracy: 0.9382
- val_loss: 0.4634
- val_accuracy: 0.9011
