# Classification-of-Italian-Wines-based-on-Chemical-Measurements-of-Color-Intensity 

Classification

In this classification setting, we use a wine dataset of chemical measurement of two variables, Color_intensity
and Alcalinity_of_ash, on 130 wines from two cultivars in a region in Italy.
The data set is a subset of a data set from https://archive.ics.uci.edu/ml/datasets/Wine, see that page or
http://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.names for information of the source of
the data.
First, read the original data in, keep the response class, and predictors Alcalinity_of_ash and
Color_intensity. We only use 2 classes (there are 3 classes in the original dataset) and we re-code them to
be y = 0 or 1. Also, we rename Alcalinity_of_ash and Color_intensity to be x1 and x2.
Then, we make plot and visualize the relation between the variables. 

we would like to use Logistic regression, LDA, and KNN methods to estimate the test error rates.
To do so, we will use the Validation Set approach. So, now we split the dataset to be the train and test
datasets. 

Compare classifiers

Compare the test error rates of the above three classifiers based on the 0.5 cut-off on posterior
probability classification rule and which method would you prefer? Why? Which one is the most flexible
classifier among the three?
