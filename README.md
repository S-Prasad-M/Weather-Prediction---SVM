#Weather Prediction using SVM
This project is about Support Vector Machines and its application. We are using SVM to predict the weather using sklearn library in python. The code is drafted in an ipynb file. SVM classifier is used as the training algorithm using weather data collect from a resource. We have achieved an accuracy of 79.6%. Then we implemented our model to predict the current weather.


A support vector machine (SVM) is a type of supervised machine learning algorithm that is used to solve two-group classification problems. It works by providing it with sets of labelled training data for each category and then using these data points to categorize new unseen data.
SVM algorithms are often faster than neural networks because they use relatively simple mathematical models that require fewer computations. Additionally, SVM algorithms are better suited to limited datasets because they are adept at finding patterns in small data and can be successfully trained on datasets with only a few thousand samples. This is because SVM algorithms can make use of kernel functions and other features to maximize their performance on small datasets.

In this prediction, the Radial basis function is best. The choice of Kernel functions is not governed by a single model. The only way to define the kernel function is by experimental comparison, based on the traits of particular samples, for better parameters and better generalisation performance. While some kernel functions perform satisfactorily, others perform poorly. In machine learning, the radial basis function kernel, or RBF kernel, is a popular kernel function used in various kernelized learning algorithms. In particular, it is commonly used in support vector machine classification.

## Process of Prediction
The main steps of predicting the weather are as follows. First, we feed the data into the program, and a series of pre-processing is carried out to extract a set of feature vectors. Then these are sent to the training I/O of SVM to train the parameters and support vectors.
Here, the data is put under square root transformation. The square root transformation makes it easier to analyse the data by making it more spread out and easier to interpret. When data is concentrated in a small range, it can be difficult to distinguish patterns or to draw meaningful conclusions from it. Applying a square root transformation to the data makes it more spread out, which makes it easier to interpret the data and draw conclusions from it.
It changes the shape of the data by redistributing the points across the range in a different way. This makes it easier to identify patterns and draw conclusions from the data, even though the values themselves may appear to be smaller.
At last, some data is inputted from the user and used to predict the results by observing the patterns of the previous data which was made by the SVC.

