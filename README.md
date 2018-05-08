# Neural-Network-using-CUDA
Batch version of 3 layer neural network has been implemented using CUDA in C++. The weight updates of the nodes in each layer in forward and back propagation have been parallelized to reduce the main overhead of batch update.
The model predicts cat vs non cat images. The network takes flattened image matrices as input.
The dataset used is CIFAR-10 and preprocessing has been done using python.
