# Neural_Network_Charity_Analysis - Module 19 - Challenge

### Overview and Purpose

The purpose of this analysis is to help Beks process a dataset of 34,000 different organizations to see if the funding from Alphabet Soup were successful. To do this we will use a neural network model and try to adjust the number of nodes/layers evaluated to achieve the highest level of accuracy.

### Results

Data Preprocessing
* What variable(s) are considered the target(s) for your model?
 * The target variable for this analysis is "IS_SUCESSESFUL".

* What variable(s) are the features for your model?
 * The feature variables for this analysis are; APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.

* What variable(s) are neither targets or features, and should be removed for the input data?
 * Variables that are neither targets nor features include; EIN and NAME, and are to be excluded from the model.

Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
 * When deciding how many neurons and layers that should be included in a neural network it is important to consider how many input features are in the model. This model has been fitted with 2 hidden layers consisting of 80 nodes, and 30 nodes, respectively. The model's two hidden layers have relu activation functions, and an output layer using the sigmoid function.
(insert 1a_model_summary)

* Were you able to achieve the target model performance?
 * The neural network model did not meet the target performance. The model's accuracy only achieved 72.9% accuracy.
(insert 1b_model_accuracy_eval)

* What steps did you take to try and increase model performance?
 * Three additional tests were performed to try and boost model performance; additional hidden nodes, additional hidden nodes and layers, and more nodes, layers, and changed activation functions. None of these changes made an improvement to the accuracy of the model.

### Summary

Using multiple different node counts and layers, including different activation functions, we were unable to produce higher than 74% accuracy with neural networks. I believe that using a Random forest model based on this supervised dataset might be a more efficient way to solve this machine learning classification problem.

Web Link: (https://github.com/ezra-deutsch/M19_Neural_Network_Charity_Analysis)
