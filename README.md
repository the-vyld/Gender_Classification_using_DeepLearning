This is a Neural Network Classificaltion Model which takes input a picture and predicts whether it is a male or a female.
We had a dataset of total 182598 images in total taken from various sources.
We used the Sequential model from Keras module. Each layer had ReLU activation except the last layer with sigmoid activation. We used Adam optimizer to set parameters like learning rate.
The model trained for 50 epochs with each epoch having 625 steps. The batch_size for training and validation dataset was set to be 256
In the end we received a training accuracy of 94.29% and validation accuracy of 94.88%.
