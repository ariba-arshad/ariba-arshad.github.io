## Back propagation from scratch on IRIS dataset

**Project description:** Designed and coded a multilayer ANN architecture gradient descent (feedforward and backward) from scratch to learn IRIS dataset using Pandas and Scikit-learn libraries.

### 1. Architecture:
  Since IRIS dataset has four features(SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm) so I used 4 neurons at the input layer. I used 5 neurons in the hidden layer(arbitrarily) and three neurons at the output layer(since there are three classes to predict).

### 2. Gradient descent:
  For activation functions, I used RELU at the hidden layer and softmax at the output layer(since there are three classes to predict). For error calculation, I used absolute error and I used one-hot encoding during training.

### 3. Results:
  29  out of  30  correct.
Accuracy= 96.67 %
loss at each output neuron=
0.008
0.954
0.962
  

