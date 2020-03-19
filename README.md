# Whelan_AlphabetSoup
Module 19 Challenge Submission

In this challenge we were asked to create a deep learning neural network model to decide whether AlphabetSoup's grant applicants are likely to succeed, attempting a 75% success rate. After cleaning, formatting, and scaling the data, I set out to create an optimized neural network. After trying many different combinations of numbers of layers and neurons and activation functions, my final model is a three hidden layer neural network with 48, 20, and 8 neurons in the first, second, and third layers respectively. Prior to arriving at this final model, I increased the first layers neurons to as high as 80, I tried models with only one or two hidden layers, and I tried substituting the relu activation function for other functions such as sigmoid and tanh.

Unfortunately, even with dozens of iterations and training my model for 500 epochs, I was only able to get my model's training accuracy as high as 74.2%, while its test accuracy never rose higher than 72.5%, suggesting that some degree of the improvements I was making to my model's training accuracy were merely overfitting the model to that set.

If I were to implement a different model to solve this problem, I would choose a Balanced Random Forest Classifier. The AlphabetSoup data set and the classification problem we are trying to solve are very well suited to this type of supervised machine learning model, as our data set has enough observations that a sophisticated ensemble classifier could identify the patterns present in the data.
