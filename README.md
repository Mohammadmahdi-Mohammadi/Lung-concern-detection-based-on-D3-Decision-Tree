# Lung-concern-detection-based-on-D3-Decision-Tree
Lung concern detection based on clinical reports is one of the primary tasks considered last decade. You are given a dataset that includes 15 clinical features for 309 people who visited Shahid Modares hospital in Shahrivar 1401. In this problem, you are asked to implement the ID3 Decision Tree to classify whether people have lung concerns.

a) Implement a Decision Tree and train a model with 25% of the dataset selected randomly; then, report the obtained tree (graph information like depth, leaves, etc.), accuracy, and confusion matric for the test set. (Note: You are only allowed to use “Numpy,” “Pandas,” and “math” libraries)

b) Repeat part (a) seven times and report mean accuracy; why are the results different? (In each model, select the training set randomly and independent of others)

c) Repeat parts (a-b) for a situation the training set is 45%, 65%, and 85% of the dataset. In your report, discuss the training set`s size effects on obtained tree`s graph and model performances or not.

d) Now, select 75% of the dataset for the training set and the remaining for testing. Implement pruning operation on the test set. Plot a line chart. The Y-axis is the accuracy measure, and X-axis is the max depth of the tree. Discuss obtained chart. (Hint: you can assume a threshold for deciding whether it is valuable to keep a node. The threshold can be applied on one or many metrics like the model`s accuracy in un/pruned states)

e) Repeat parts (a-d) using sklearn built-in functions and compare them with your results; Discuss differences.
