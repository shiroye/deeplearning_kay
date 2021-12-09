# deeplearning_kay
A pretrained model has been created for user access review and a prediction can be made as follows:
Provide names of users of a company and prediction can be made of a username most likely used by the user

This was achieved using residaul model with the following parameters and hyperparameters

ff_dim = 128
embed_dm = 128
activation function for the hidden layer - tanh
activation function for the output layer - softmax
Total trainable parameters of 363,129

optimizer = adam
loss = Categorical Cross Entropy
Validation = 20%
Test data  = 10%

1. load the pretrained model and the summary
2. load the data to be predicted 
3. the data also need to go through the preprocessing to convert 
it from text to number that can be used for a prediction
4. make a prediction
5. This can be compared to what is expected to determine the accuracy of the prediction
