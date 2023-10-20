# hybrid-parallel-SGD
# Hybrid Data Parallelism for Efficient Neural Network Training

## Abstract

Stochastic Gradient Descent is used for large datasets to train models to reduce the training time. On top of that data parallelism is
widely used as a method to efficiently train neural networks using
multiple worker nodes in parallel. Synchronous and asynchronous
approach to data parallelism is used by most systems to train the
model in parallel. However, both of them have their drawbacks.
We propose a third approach to data parallelism which is a hybrid
between synchronous and asynchronous approaches, using both approaches to train the neural network. When the threshold function
is selected appropriately to gradually shift all parameter aggregation from asynchronous to synchronous, we show that in a given
time period our hybrid approach outperforms both asynchronous
and synchronous approaches.
