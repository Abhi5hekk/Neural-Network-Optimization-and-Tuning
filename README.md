# Neural-Network-Optimization-and-Tuning
I've learned how to build computational graphs in PyTorch and compute gradients. The final piece to training a network is applying the gradients to update the network parameters. In this tutorial I shall learn how to implement a number of optimization techniques in PyTorch along with other tuning methods.

I uses the PyTorch dataset API to load a dataset with exactly the same properties as the MNIST handwritten digits dataset. However, instead of handwritten digits, this dataset contains images of 10 different common clothing items, hence the name Fashion-MNIST . Performance on MNIST saturates quickly with simple network architectures and optimization methods. This dataset is more difficult than MNIST and is useful to demonstrate the relative improvements of different optimization methods.

Some of the characteristics are mentioned below.

1. 28x28 images 

2. 10 classes

3. Single color channel (B&W)

4. Centered objects

5. 50000 training set members

6. 10000 test set members
