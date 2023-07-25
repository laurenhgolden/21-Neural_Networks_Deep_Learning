# 21_Neural_Networks_Machine_Learning_Challenge

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

1. Preprocess the Data: this includes dropping unnecessary columns, binning data for columns with more than 10 unique values, encoding the variables, splitting the preprocessed data into training and testing groups and standard scaling the data
2. Compile, Train, and Evaluate the Model: this includes creating a neural network by assigning the number of input features and nodes for each layer using TensorFlow and Keras, creating the first layer and the hiddln layer, compiling the model and then training it. Finally, we evaluate the model to test teh data to determine the loss and the accuracy. 
3. Optimize the Model: In order to do this, I binned additional data in the Income_Amt column, added an additional hidden layer, added neurons to the hidden layers and changed the activation function from 'relu' to 'tanh' for the newly added layer. I also added 50 epochs.
4. Write a Report on the Neural Network Model: this explains in more detail my processing and rationale.

# Tools
- Python
- sklearn
- TensorFlow
- Google Colab