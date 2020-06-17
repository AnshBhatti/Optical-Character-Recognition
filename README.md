# Optical-Character-Recognition
Optical Character Recognition (for digits only) implemented using Torch

Description and specifics:
- Uses the default Torch's MNIST dataset for images of single numerical digits, which were filtered into 28 x 28 squares.
- Neural network contains 1 input layer, 2 hidden layers, 1 output layer
- Training is done using 15 epochs
- Model is created using Linear and LogSoftmax regressions
- Loss is calculated using Negative Log Loss method (due to Softmax Regression used in the output layer)

Inspiration:
- Practicing neural network building and training
