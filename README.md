# weight-init-notes
Weight initialization for neural nets


## Xavier init

- Paper: Understanding the difficulty of training deep feedforward neural networks 
- Blog: [link](https://prateekvjoshi.com/2016/03/29/understanding-xavier-initialization-in-deep-neural-networks/)
- Summary: Weight can be initialized by Gaussion distribution with 1/n variance and n is the number of input dimension. This can keep the output and intput have the same variance.

## magnitude of weights matters
- Paper: Han, Song, et al. "[Learning both weights and connections for efficient neural network.](http://papers.nips.cc/paper/5784-learning-both-weights-and-connections-for-efficient-neural-network)" Advances in Neural Information Processing Systems. 2015.
- Comment: large weights play a more important role than smaller ones

