# hybrid-parallel-SGD
# Hybrid Data Parallelism for Efficient Neural Network Training

## Abstract

Stochastic Gradient Descent (SGD) is a crucial tool for accelerating the training of models on large datasets. In addition to this, data parallelism is widely employed as a technique to efficiently train neural networks using multiple worker nodes in parallel. Commonly, two approaches are used: synchronous, where all nodes collaborate simultaneously, and asynchronous, where nodes work more independently. However, both of these methods have their limitations.

