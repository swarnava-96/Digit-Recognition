# Digit-Recognition
### Goal: The Goal of this mini project is to recognize digits using ANN on Keras MNIST data set.

### About the data set: 
I have used the Keras inbuilt MNIST data set that contains 70K 28x28 gray scale images of 10 digits (0-9).

### Project Description:
I have loaded the data into train and test sets and scaled down between 0-1. A three layer neural network ANN model was built. Initially, the first layer was flattened from 2D to 1D. Then a Dense layer was added having 128 neurons with activation function relu and finally an output layer was added with 10 output classes and activation function as soft max.
Then the model was trained for 10 epochs with optimizer as Adam, loss as sparse categorical cross entropy, metrics as accuracy and with a batch size of 64. Model performed well giving a training accuracy of 99% and validation accuracy of 97.6%. 

The below image shows the training vs validation loss:

![image](https://user-images.githubusercontent.com/75041273/137603589-9e01dbc4-af6e-4044-b3af-2e62002d6a36.png)

The below image shows the training vs validation accuracy:

![image](https://user-images.githubusercontent.com/75041273/137603606-38a517cf-fcc1-448e-aae1-420209ad8650.png)
