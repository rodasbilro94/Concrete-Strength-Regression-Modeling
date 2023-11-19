Concrete Strength Regression Modeling
In this project, I created regression models using the Keras library to predict concrete compressive strength based on various input features. The dataset I used for this project contains information about different predictors related to concrete properties.

Dataset Description
The dataset includes the following predictors:

Cement
Blast Furnace Slag
Fly Ash
Water
Superplasticizer
Coarse Aggregate
Fine Aggregate
Age
The target variable is the "Strength," which represents the concrete's compressive strength.

Project Tasks
A. Baseline Model
In this task, I created a baseline regression model with the following specifications:

One hidden layer with 10 nodes and a ReLU activation function.
Adam optimizer and Mean Squared Error (MSE) loss function.
Data split: 70% for training and 30% for testing.
I repeated the following steps 50 times:

Split the data into training and testing sets.
Train the model on the training data for 50 epochs.
Evaluate the model on the testing data and calculate the Mean Squared Error (MSE).
I reported the mean and standard deviation of the MSE.

B. Normalize the Data
In this task, I repeated the Baseline Model task but used normalized data. Data normalization involved subtracting the mean and dividing by the standard deviation of each predictor. I then compared the mean MSE with that of the Baseline Model.

C. Increase the Number of Epochs
Here, I repeated the Data Normalization task but increased the number of training epochs to 100. I compared the mean MSE with that of the Data Normalization task.

D. Increase the Number of Hidden Layers
In this task, I used a neural network with three hidden layers, each consisting of 10 nodes and ReLU activation. I repeated the Data Normalization task with this new architecture and compared the mean MSE with that of the Data Normalization task.

Conclusion
This project explored the impact of data normalization, the number of training epochs, and the number of hidden layers on the performance of regression models for predicting concrete compressive strength. The results are summarized in terms of mean MSE for each task.