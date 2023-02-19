# CNN-hyperparameter_tuning
This Python code performs a grid search using scikit-learn to find the optimal combination of batch size and epochs for a neural network model built with Keras.

# Prerequisites
To run this code, you need the following libraries:

NumPy
scikit-learn
Keras
The data set used in this code is "pima-indians-diabetes.data.csv". Make sure that the file is in the correct path ("D:" in this code) or change it accordingly to the path where the file is located.

# How to Use
To run the code, simply execute the Python script. The output will display the best combination of batch size and epochs, as well as the mean and standard deviation of the results for each combination tested.

You can modify the values for batch_size and epochs to your desired list of values, and add or remove values as necessary. The n_jobs parameter can also be modified to adjust the number of CPU cores to be used for parallel computation. If you have a low amount of memory available, you can set n_jobs=None to avoid running out of memory.

# Code Structure
Import required libraries
Define a function to create the Keras model
Set the random seed for reproducibility
Load the dataset and split into input and output variables
Create the KerasClassifier model
Define the grid search parameters
Perform the grid search using GridSearchCV
Summarize the results, showing the best combination of batch size and epochs, and the mean and standard deviation of the results for each combination tested.
