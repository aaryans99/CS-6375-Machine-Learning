# Assignment 2

Created a neural network without using libraries.

## Description

[Dataset](https://archive.ics.uci.edu/dataset/477/real+estate+valuation+data+set) - The market historical data set of real estate valuation are collected from Sindian Dist.,
New Taipei City, Taiwan.

We have created a Neural Network class which consists of various functions to calculate performance metrics as well as to apply
forward and backword propagation on the dataset.

Instead of tuning hyperparameters manually we have used a loop to pass down different learning rates to find out the most convenient
performance metrics. 

Random state values have been changed manually to find out the most suitable value.

For ReLu activation our data was overflowing so we had to tweak the network and create a new function for it.

# Conclusion
We found out that tan hyperbolic x was the most suitable activation function for prediction. If we had more data, we could have tweaked
sigmoid and ReLu function for better performance.

## Getting Started

### Dependencies

* Google Colaboratory

### Executing program

* Click on play button beside each cell to run the code.

## Authors

Aaryan Singh - axc230019<br>
Nikunj Gohil - ndg220000



## Acknowledgments

Inspiration, code snippets, etc.
* [Gradient Descent](https://www.kaggle.com/code/procode/neural-network-without-libraries)
