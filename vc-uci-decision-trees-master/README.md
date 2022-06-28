# Vertebral Column Dataset Analysis

Use Decision Trees for analyze the VC dataset and predict new cases.

Comments:

- Brute force approach used to identify ideal number of parameters.
- The dataset was stratified during the splitting process to maintain the proportion of data records that belong to the separate multiple classes. The impurity measures that have been used are ‘Entropy’ and ‘Gini Index’ to compare the performance for the both and decide to select the best one based on the accuracy of the results produced.
- To prevent over-fitting in the decision tree modelling, we have used certain parameters to set constraints on the tree size, such as ‘Maximum Depth’ and ‘Minimum Samples for a node splits’ (to control for over-fitting).
- Confusion Matrix has been generated. Graphviz has been used to generate graphs. All figures can be found in the repo.

Conclusion:
We have been able to achieve a prediction accuracy varies in a range of ~75% to 90% which is commendable. 
The selection of impurity measures (between Gini and Entropy) could not be seen to produce significant differences due to the relatively smaller size of the dataset, but given a larger dataset, the results should be more differentiable.
