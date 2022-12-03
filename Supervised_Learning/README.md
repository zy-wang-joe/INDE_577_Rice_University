# Supervised Learning
## Table Content
- Introduction
- How Supervised Learning Works
    - Classification
    - Regression
- Algorithms
    - K-Nearest Neighbor
    - Linear Regression
    - Logistic Regression
    - Perceptron
    - Multilayer Neural networks]
    - Decision Tree
    - Ensemble Learning and Random Forest
- Reference

## Introduction
**Supervised learning**, also known as supervised machine learning, is a subcategory of machine learning and artificial intelligence. It is defined by its use of labeled datasets to train algorithms that to classify data or predict outcomes accurately. As input data is fed into the model, it adjusts its weights until the model has been fitted appropriately, which occurs as part of the cross validation process. Supervised learning helps organizations solve for a variety of real-world problems at scale, such as classifying spam in a separate folder from your inbox.


## How supervised learning works

Supervised learning uses a training set to teach models to yield the desired output. This training dataset includes inputs and correct outputs, which allow the model to learn over time. The algorithm measures its accuracy through the loss function, adjusting until the error has been sufficiently minimized.

Supervised learning can be separated into two types of problems when data mining—classification and regression:

- **Classification** uses an algorithm to accurately assign test data into specific categories. It recognizes specific entities within the dataset and attempts to draw some conclusions on how those entities should be labeled or defined. Common classification algorithms are linear classifiers, support vector machines (SVM), decision trees, k-nearest neighbor, and random forest, which are described in more detail below.
- **Regression** is used to understand the relationship between dependent and independent variables. It is commonly used to make projections, such as for sales revenue for a given business. Linear regression, logistical regression, and polynomial regression are popular regression algorithms.


## Algorithms
Various algorithms and computation techniques are used in supervised machine learning processes. Below are brief explanations of models learned in class:

### K-Nearest Neighbor
K-nearest neighbor, also known as the KNN algorithm, is a non-parametric algorithm that classifies data points based on their proximity and association to other available data. This algorithm assumes that similar data points can be found near each other. As a result, it seeks to calculate the distance between data points, usually through Euclidean distance, and then it assigns a category based on the most frequent category or average.  
Its ease of use and low calculation time make it a preferred algorithm by data scientists, but as the test dataset grows, the processing time lengthens, making it less appealing for classification tasks. KNN is typically used for recommendation engines and image recognition.  

### Linear Regression
Linear regression is used to identify the relationship between a dependent variable and one or more independent variables and is typically leveraged to make predictions about future outcomes. When there is only one independent variable and one dependent variable, it is known as simple linear regression. As the number of independent variables increases, it is referred to as multiple linear regression. For each type of linear regression, it seeks to plot a line of best fit, which is calculated through the method of least squares. However, unlike other regression models, this line is straight when plotted on a graph.

### Logistic Regression
While linear regression is leveraged when dependent variables are continuous, logistical regression is selected when the dependent variable is categorical, meaning they have binary outputs, such as "true" and "false" or "yes" and "no." While both regression models seek to understand relationships between data inputs, logistic regression is mainly used to solve binary classification problems, such as spam identification.

### Perceptron
A Perceptron is an algorithm for supervised learning of binary classifiers. It's a simplified model of a biological neuron, and it is a type of linear classifier, i.e., a classifier that makes its predictions based on a linear predictor function combining a set of weights with the feature vector.

### Multilayer Neural networks
Primarily leveraged for deep learning algorithms, neural networks process training data by mimicking the interconnectivity of the human brain through layers of nodes. Each node is made up of inputs, weights, a bias (or threshold), and an output. If that output value exceeds a given threshold, it “fires” or activates the node, passing data to the next layer in the network. Neural networks learn this mapping function through supervised learning, adjusting based on the loss function through the process of gradient descent. When the cost function is at or near zero, we can be confident in the model’s accuracy to yield the correct answer.A multilayer neural network is multilayer of perceptrons. It consists an input layer, several hidden layers, output layer, fully connected weights and non-linear activation function. 

### Decision Tree
A decision tree is a decision support tool that uses a tree-like model of decisions and their possible consequences, including chance event outcomes, resource costs, and utility. It is one way to display an algorithm that only contains conditional control statements.Decision trees are commonly used in operations research, specifically in decision analysis, to help identify a strategy most likely to reach a goal, but are also a popular tool in machine learning.  

### Ensemble Learning and Random Forest
**Ensemble learrning** is a group of predictors, and it makes decision by majority vote for classification (hard voting classifier) and averaging for regression. It's a kind of Supervised learning, which uses multiple learning algorithms to obtain better predictive performance than could be obtained from any of the constituent learning algorithms alone. Unlike a statistical ensemble in statistical mechanics, which is usually infinite, a machine learning ensemble consists of only a concrete finite set of alternative models, but typically allows for much more flexible structure to exist among those alternatives.  
**Random Forest** is perhaps the most popular ensemble learning method for classification and regression. It constructs a multitude of decision trees at training time. For classification tasks, the output of the random forest is the class selected by most trees. For regression tasks, the mean or average prediction of the individual trees is returned. Random forest correct for decision trees habit of overfitting to their training set. Random forest generally outperforms decision trees.  


## Reference
1.Wikimedia Foundation. (2021, November 2). Supervised learning. Wikipedia. Retrieved December 13, 2021, from https://en.wikipedia.org/wiki/Supervised_learning. 
2.IBM Cloud Education. (n.d.). What is supervised learning? IBM. Retrieved December 13, 2021, from https://www.ibm.com/cloud/learn/supervised-learning. 
