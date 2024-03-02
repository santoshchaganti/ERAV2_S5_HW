# _ERAV2 Session 5 Homework_

## _HomeWork Description:_
> _*This Homework contains Basic implementation of Neural Network on MNIST dataset. The main goal is to understand how a neural network works and how to model a neural network*_

## _File Descriptions:_
- `utils.py` -- It contains the utility functions. It has Function named `train()` which will calculate loss function and backpropagation method. and function `test()` will test_loss, correct prediction gives the accuracy. finally function `plot()` will calculate the `Training Loss`, `Training accuracy`, `Test Loss`, `Test Accuarcy` from functions `train()` and `test()`.

- `model.py` -- having Class `Net` is basically a model/convolve of neural network architecture with convolutions and fully connected layers and configurations of these layers. The model takes input, applies convolutional operations, ReLU activations, max-pooling, and fully connected layers to output predictions.

- `S5.ipynb` -- It contains and uses `utils.py` and `model.py` functions. It also contains downloading MNIST dataset and loading it to my env. Then I started training the MNIST with my Neural Network Architecture. After that I evaluate the performance and plotted a graph for train, test -- loss and accuracies.
