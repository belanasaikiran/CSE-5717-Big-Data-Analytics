# HomeWork Tasks

## HW 4

### Fashion-MNIST with MLP

In this assignment, we will complete the following tasks:

- build a MLP classifier for the Fashion-MNIST dataset.
- use PCA to reduce the dimensionality of the dataset, and make sure we preserve 95% of the explained variance. (20 points)
- train a classifier using the dimensionality reduced dataset with the same network topology as the previous classifier,  and compare the classification accuracy result with the one using the original dataset. (10 points)
- check whether we observe anything surprising. (10 points)
- follow and improve the example from the text to fine tune the neural network hyperparameters using RandomizedSearchCV. Note to use the dataset after the PCA step. This will make the search less time consuming. (40 points)
- report the test result using the best model obtained from the randomized search. Show the summary of the model. Compare this result with the previous results. (20 points)s


## HW 5

In this assginment, we try to build a classifier for the Fashion-MNIST dataset that achieves over 94% accuracy on the test set. 

To achieve this goal, we
- use convnet for this purpose
- learn how to use padding in convnet
- learn how to use Batch Normalization and Dropout when training deep neural networks
- learn how to use nadam optimizer
- add more layers to the existing network model in function build_model()
- use validation data and observe the training history to determine whether the model is good enough to run test data
- use test data set only once.

This assignment is graded on the test accuracy. Any accuracy below 93% is graded as 0; any accuracy above 94% is graded as 100. Any grade in between is graded using the formula  (acc - 0.93)/(0.94 - 0.93), 1))*100.