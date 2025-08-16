## Dataset: Fashion MNIST data (url - https://www.kaggle.com/datasets/zalando-research/fashionmnist)

## Approach:
Explored multiple deep learning architectures for Fashion-MNIST classification:
- ANN1: Simple feedforward neural network with two hidden layers (128, 64).
- ANN2: Improved ANN with batch normalization, dropout, and L2 regularization.
- ANN3: Hyperparameter tuning using Optuna to optimize learning rate, batch size, and architecture.
- CNN1: Basic CNN with two convolutional blocks — each consisting of convolution, ReLU activation, batch normalization, and max pooling.
- VGG16 Fine-Tuning: Transfer learning by fine-tuning the ImageNet-pretrained VGG16 model for Fashion-MNIST.
