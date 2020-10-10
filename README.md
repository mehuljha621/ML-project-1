# ML-project-1
Predicting product sales through ads delivered on Social Networking Sites using k-N.N. in Python

The k-NN algorithm is among the simplest of all machine learning algorithms. The input consists of the k closest training examples in the feature space while the output depends on whether k-NN is used for classification or regression:
In k-NN classification, the output is a class membership. An object is classified by a majority vote of its neighbors, with the object being assigned to the class most common among its k nearest neighbors (k is a positive integer, typically small). If k = 1, then the object is simply assigned to the class of that single nearest neighbor.

The Dataset contains information about users on a Social Networking site and using that info as Features for our ML model,
we try to predict that whether a particular user after clicking on a ad on the Social networking site goes on to buy a particular product or not.
Well this particular Social Network has a Business client which lets assume is a car company which advertises itself by putting adds on the social networking site.
Now the work of the social network here is to gather information as to whether the user bought the product or not.
The dependent variable in this case is Purchased which is 1 if user purchases the car and 0 otherwise.
So the goal here is to create a classifier which would put each user into the correct category by predicting as to whether he's buying the product or not.
