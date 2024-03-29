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