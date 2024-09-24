 || K-Nearest Neighbors ||
 This algorithm is a classification algorithm used to predict the class of a new or unknown case based on its similarity to other cases. 
 The algorithm works by selecting a value for K, calculating the distance between the new case and each case in the dataset, finding the K nearest neighbors, 
 and predicting the response of the unknown data point based on the most popular response value from the K nearest neighbors. The choice of K is important, 
 as a low value can result in overfitting and capturing noise in the data, while a high value can lead to an overly generalized model. The similarity between 
 cases is calculated using measures such as Euclidean distance. To determine the best value for K, a part of the data is reserved for testing the accuracy of 
 the model. Nearest neighbors analysis can also be used to compute values for a continuous target.

|| Decision Trees ||
Built by splitting the training set into distinct nodes, where each node contains data from one category. The goal is to use the decision tree to predict the class of an unknown case, such as determining which drug to prescribe to a patient based on their characteristics. The decision tree is built by considering attributes one by one and calculating their significance in splitting the data. The tree is then used to predict the class of unknown cases.
