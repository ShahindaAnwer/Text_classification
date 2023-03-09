# Text_classification

## Problem Statement

Proper communication a vital part of being human. The world has become very connected, therefore, with as many languages as there are, translation provides a critical cultural and economic bridge between people from different countries and ethnic groups.

## Model

### RNN:
A recurrent neural network is needed as it allows time-series context to flow through the network. RNNs take in sequences of text as inputs or return sequences of text as outputs, I used a many-to-many process where the input is a sequence of English words and the output is a sequence of French words.

![RNN](https://user-images.githubusercontent.com/62629426/222014075-63851463-0c0e-4ad9-9d37-44d530699082.png)

Each rectangle is a vector and arrows represent functions, the green vectors hold the RNN’s state

### Libraries: 
- [Tensorflow - Keras](https://www.tensorflow.org/api_docs/python/tf/keras)
- [tensorflow](https://www.tensorflow.org/)
- [Numpy](https://numpy.org/)
- [Unicodedata](https://docs.python.org/3/library/unicodedata.html)
- [String](https://docs.python.org/3/library/string.html)
- [Re](https://docs.python.org/3/library/re.html)

### Results:
Specific translations of English to French

### Accuracy:
- loss: 0.3833
- val_loss: 2.1110
