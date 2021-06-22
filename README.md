# Sparse Orthogonal Variational Inference for Gaussian Processes 
Jiaxin Shi, Michalis K. Titsias, and Andriy Mnih, AISTATS 2020. [https://arxiv.org/abs/1910.10596](https://arxiv.org/abs/1910.10596)

<img src="results/movie.gif" width="800">

Code for reproducing the animation: 
```
solvegp.ipynb
```

## Deep Convolutional Gaussian Processes for CIFAR10 Classification

Thanks to Shengyang Sun @ssydasheng who reproduced the experiments in
https://github.com/ssydasheng/Harmonic-Kernel-Decomposition/blob/master/exp/classification.py,
where setting the `--method` option to `sovgd` corresponds to SOLVE-GP (The setting is slightly different from the original paper with comparable results).
Also see the [accompanying paper](https://arxiv.org/abs/2106.05992) for our latest development that leads to even better results. 

## Dependencies
```
Tensorflow >= 1.4
GPflow == 1.5.1
```
