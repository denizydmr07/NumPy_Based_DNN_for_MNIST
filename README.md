# MNIST Digit Recognition with NumPy-Based Deep Neural Network

### Overview
This project involves building a deep neural network (DNN) using only the NumPy to classify handwritten digits from the MNIST dataset.

### Gradient Descent
* I trained the model using batch gradient descent.
* Cross-entropy loss is minimized by adjusting the model's weights and biases with back propagation.
* I used the ReLU activation function in the hidden layer and stable softmax activation in the output layer.
* I saved the best weights and biases with monitoring validation accuracy.

### Model Structure

```bash
Input Layer (784 nodes representing the flattened 28x28 pixel images) 
    |
    v
Hidden Layer (784 nodes with ReLU activation)
    |
    v
Output Layer (10 nodes representing digit classes, with stable softmax activation)
```

### Results
* Train Accuracy: 0.87
* Validation Accuracy: 0.86
* Test Accuracy: 0.87
