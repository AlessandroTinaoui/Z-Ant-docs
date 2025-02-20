# Core

The core of the project consists of tensors, quantization, and tensor mathematics.

## Tensor module

### overview 

Tensors are multi-dimensional arrays that can represent scalars, vectors, matrices, and higher-dimensional data. A scalar is a 0-dimensional tensor, a vector is a 1-dimensional tensor, and a matrix is a 2-dimensional tensor. This can extend to even higher dimensions.

### usage

Tensors are essential for representing and processing data in neural networks, enabling complex inputs like images, text sequences, or tabular data. Each neuron processes tensors through mathematical operations like matrix multiplication and weighted sums to compute outputs.

Common tensor applications in NN:

* Data Input: Images are represented as 3D tensors (height, width, color channels).
* Weights and Biases: Internal parameters (weights and biases) are tensors updated during training.
* Forward Propagation: Tensors are used to compute model outputs in inference by performing matrix operations.
* Optimization: Gradients are also tensors used to update model parameters during training.


#### crating a tensor 

//CHIEDERE//


## Tensor math

This package contains all of the class necessary to perform every math operations. 

### overview

#### why switching to lean_tensor_math.zig?

Since we need this project to run on less powerful systems, we must optimize performance by skipping safety checks and always returning void.

### usage

Its goal is to efficiently compute any mathematical tensor operation that may prove useful in a variety of applications.

## quantization