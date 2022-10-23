# Decision Tree
## Table of Contents
- Introduction
- Algorithm
- Parameters
- Evaluation
- Dataset

## Introduction
Decision Trees (DTs) are a non-parametric supervised learning method used for classification and regression. The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features. A tree can be seen as a piecewise constant approximation.

When used for classification, Decision Tree starts with a root node of a tree then compares the value of different attributes and follows the next branch until it reaches the end leaf node. It uses different algorithms to check about the split and variable that allow the best homogeneous sets of population. When making predictions about new samples, the samples are routed down the tree and reach a final end leaf node. The predicted class for a test sample is the majority vote of all training samples in that leaf node.

1. Tree structure : internal nodes indicate features, while leaf nodes represent classes
2. Start from root, choose a suitable feature xi and its split point ci at each internal node, split the node to two child nodes depending on whether xi <= ci , until the child nodes are pure
3. Equivalent to rectangular partition of the region

## Algorithm
1. It begins with the original set S as the root node.
2. On each iteration of the algorithm, it iterates through the very unused attribute of the set S and calculates impurity of this attribute.
    - Gini Index
    - Information Gain
    - Misclassification Error
3. It then selects the attribute which has the largest impurity.
4. The set S is then split by the selected attribute to produce a subset of the data.
5. The algorithm continues to recur on each subset, considering only attributes never selected before util a stopping criterion below is reached
    - All samples in the node have the same class
    - Number of samples in the node smaller than or equal to the specified minimum number of samples required to split the node
    - The tree has reached maximum depth