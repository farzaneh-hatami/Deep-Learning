# Impelementing Artificial Neural Networks from Scartch with python

In this project Fully Connected Neural Networks is implemented from Scratch for 3 diffrent tasks:
- **Regression** for age estimation
- **Multi-label classification**  for race prediction
- **Logistic Regrresion** for gender prediction 


In this project backpropagation is implemented from scratch and the network has the the ability of adding different layers, It also contains multiple multiple activation functions like ReLU, Softmax and different loss functions like MSE, negative log likelihood.

## Dataset
[UTKFace dataset](https://susanqq.github.io/UTKFace) is used for training and evaluation of Network for all the tasks. 
For data prepration step Normalization and Dimensionality Reduction are applied to the data.


## Results for different tasks
We compare loss per trial for:
  - zero weight initialization
  - Xavier weight initialization
  - -0.1 to 0.1 random weight initialization.
  - He weight initialization
  - STep decay learning rate adaption

### Regression
The regression task predicts age of each face image in dataset. The Implemented Network achoeve a MSE of 346 after training.

### multi-label classification
The classification task prdeicts the race of each image in dataset.


### Logistic Regrresion
The logoostic regression task predicts the gender of eache image in dataset.
For this purpose sigmoid activation function and logistic loss function is implemented.

