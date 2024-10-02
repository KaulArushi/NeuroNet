I've created a neural network trained with backpropagation in an order to attempt to use input to predict output using Python.
Problem Explanation: Consider trying to predict the output column given the three input columns.
Solution Approach: We could solve this problem by simply measuring statistics between the input values and the output values. If we did so, we would see that the leftmost input column is perfectly correlated with the output.
Backpropagation, in its simplest form, measures statistics like this to make a model. Let's jump right in and use it to do this.
2 Layer Neural Network: https://github.com/KaulArushi/NeuroNet/blob/main/2%20Layer%20Network 
After having a look at the above link; We now know  how the network updates, let's look back at our training data and reflect. When both an input and a output are 1, we increase the weight between them. When an input is 1 and an output is 0, we decrease the weight between them.
This phenomenon is what causes our network to learn based on correlations between the input and output.
Looking at '3 Layer Neural Network': https://github.com/KaulArushi/NeuroNet/blob/main/3%20Layer%20Neural%20Network
The output of the first layer (l1) is the input to the second layer.
We, now know that when we Consider trying to predict the output column given the two input columns; neither columns have any correlation to the output. Each column has a 50% chance of predicting a 1 and a 50% chance of predicting a 0.
This is considered a "nonlinear" pattern because there isn't a direct one-to-one relationship between the input and output. Instead, there is a one-to-one relationship between a combination of inputs.
This is similar to image recognition problem!
Note: The field of adding more layers to model more combinations of relationships such as this is known as "deep learning" because of the increasingly deep layers being modeled.
