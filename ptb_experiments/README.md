
## Recurrent neural network for word-level language modelling

Python notebook (word_lstm_ptb.ipynb) to replicate the results from:

Zaremba, Wojciech, Ilya Sutskever, and Oriol Vinyals. "Recurrent neural network regularization." arXiv preprint arXiv:1409.2329 (2014).

on the Penn Tree Bank dataset (downloaded from http://www.fit.vutbr.cz/~imikolov/rnnlm/simple-examples.tgz) using theano and lasagne

Three model sizes: small (test perplexity ~118), medium (test perplexity ~84) and large

Code was written based on the examples

in torch: https://github.com/wojzaremba/lstm

in tensorflow: https://github.com/tensorflow/models/tree/master/tutorials/rnn/ptb
