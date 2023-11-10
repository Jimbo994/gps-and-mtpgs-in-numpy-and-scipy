# gps-and-mtpgs-in-numpy-and-scipy
Simple GP and Multi-task GP implementation in numpy and scipy

I Coded up simple GPs and Multi-Task GPs in Numpy and Scipy to familiarize myself with inner workings of (MT)GPs.
This code is very basic and can for example be further improved by the following:
- normalizing inputs between 0 and 1, and standardizing outputs to zero mean and unit variance.
- More robust fitting of kernel hyperparameters (multi-start, or other solvers). This is especially beneficial for the Multi-task implementation.
- More efficient ways of constructing the Gram matrix in the Multi-task case.

Hopefully, this will enlighten others.
