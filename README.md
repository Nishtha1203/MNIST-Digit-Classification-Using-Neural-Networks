# MNIST-Digit-Classification-Using-Neural-Networks

This repository contains a simple implementation of neural networks using TensorFlow and Keras to classify handwritten digits from the MNIST dataset. The project includes steps for data preprocessing, model creation, training, evaluation, and visualization of results.


  - Single-Layer Neural Network
The first model, a simple single-layer neural network with 10 output neurons and a sigmoid activation function, achieved 92.83% accuracy on the test dataset after 10 epochs of training. This model provides a baseline for digit classification, but its simplicity limits its ability to capture more complex features in the MNIST dataset.

  - Multi-Layer Neural Network
The second model incorporated a hidden layer with 100 neurons and ReLU activation, in addition to the output layer with 10 neurons using sigmoid activation. This architecture allowed the model to learn more intricate patterns in the data. As a result, it achieved a significantly improved 97.21% accuracy on the test dataset after 10 epochs.

  - Confusion Matrix and Visualization
For both models, confusion matrices were generated to visualize classification performance. The heatmaps of the confusion matrices clearly showed better classification accuracy for the multi-layer model, with fewer misclassifications compared to the single-layer model.

  - Conclusion
The addition of a hidden layer in the second model led to a substantial improvement in accuracy, highlighting the importance of incorporating non-linear transformations and feature learning in neural network architectures. 
