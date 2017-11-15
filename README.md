# CourseraMachineLearning

## Types of learning algorithm

- Linear regression
- Logistic regression
- Neural networks

## Regularization

Regularization is used to "smoothen" the learned function to make sure it doesn't overfit the data. It is based on a _lambda_ parameter, which can be choosed using a **Validation Curve**. It is implemented in exercise 5. The validation curve is a plot of the error as a function of different lambdas on the training and cross-validation sets. We pick the lambda that has the lowest cost on the cross-validation test.

## Debugging a learning algorithm

### Plot the learning curve

The learning curve is a tool to see if there is high variance or high bias in the learning algorithm. It is implemented in exercise 5. You need to plot the cost error as a function of 'm' training examples. If the curves meet high, it means there is high bias. If the curves don't meet, it means high variance.

### Plot the validation curve

### Fixing high **variance**
Def variance : Overfitting the data

- Get more training examples
- Try smaller set of features
- Increase lambda

Note : It is better to have higher variance because it can be fixed using regularization.

### Fixing high **bias**
Def bias : Underfitting the data

- Get additional features
- Try polynomial features
- Decrease lambda