# Develop-Logistic-Regression-Model
UCLA Master of Applied Economics Econ 413 Assignment
# Train and Test Logistic Regression Model
Once you have completed the Logistic Regression assignment:

This assignment will read the data from the file iristrain-1.csv to train the Logistic Regression algorithm parameters. Once you have trained the algorithm, you will use iristest-1.csv to test to determine accuracy of your training algorithm (use threshold 1 if greater than 0.5 else 0 - see below). Compare the estimates with the actual results in the (last column) of the test file and determine the percentage accuracy from 20 training examples. 

HINTS:

- Your Experience will be matrix X and Y. Dimension of X will be 4x80 while Y will be 1 x 80. In other words, you have 80 training examples and 4 features (x1, x2, x3, and x4).

- Note that you have 20 entries to test your model.

- Assuming you have determined w1, w2, w3, w4, and b as parameters of the model, you will estimate yhat for a new row (x1, x2, x3, and x4) from the test set as per the following:

      if  sigma(w1 x1 + w2 x2 + w3 x3 + w4 x4 + b) > 0.5 yhat = 1 else yhat = 0

Where sigma is the sigmoid function.

# Compare Compute Efficiency of Loops and Matrices Implementation in Logistic Regression
In this assignment, you will compare the time the two implementation will take. Your program should record initial time ti and final time tf for each implementation to determine tloops and tmatrix. The program should print both of these times properly formatted and with descriptions. You should be able to reuse some of the code from the notebook mentioned above.
