# Regression-Model-Keras


Downloaded a dataset regarding concrete

Our goal is to find how strong the concrete is based on 8 other features.

Checked for null values, and split the data in target variable y and predictor features as X

Did Prediction in 3 ways:

1. Imported  Keras module and other necessary Libraries

2. Created a basic CNN, with an Input Layer, a hidden layer with 10 nodes in it and the compiled the model using a function regression_model().

3. I split the data into train and test sets, fit the model, and test the data using unseen data and calculated mean squared error for 50 iterations using 50 epochs to fit the model.

4. Calculated mean of mean squared error 

5. Then I Normalized the X features data and again fit and test the CNN model with the sae number of epochs, calculated the mean of mse again. Plotted a training vs validation curve

6. Then in my next step, I have utilized 100 epochs and again calculate the mean of mse for the new model.

7. Then I created another CNN Model where I added one more hidden layer with 10 nodes to it, making 2 hidden layers and fit the model using 50 epochs and calculated the mean of mean squared error.

















