I've created a neural network trained with backpropagation in an order to attempt to use input to predict output using Python.
Problem Explanation: Consider trying to predict the output column given the three input columns.
Solution Approach: We could solve this problem by simply measuring statistics between the input values and the output values. If we did so, we would see that the leftmost input column is perfectly correlated with the output.
Backpropagation, in its simplest form, measures statistics like this to make a model. Let's jump right in and use it to do this.
