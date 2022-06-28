# vc-uci-random-forest-bayesian-classifiers

# Introduction
The primary objective of this report is to document the results post the implementation of several predictive modelling approaches on the vertebral column dataset obtained from the UCI website. Firstly, we construct a random forest classifier and discuss the results as required in the assignment and subsequently move on to contrasting its performance to a naïve Bayes classifier using Python (Jupyter notebook).

# Results

- Best Random Forest Classifier Accuracy of 90.322% with number of estimators set to 8 (number of component trees). The test-train split is adjusted to 0.4.

- Feature Importance is calculated in the notebook. The accuracy and feature importance table for the comparison between the selected RFE and its component trees has also been measured.

- The Random Forest Classifier is an ensemble of several decision trees that has been constructed on data based on its entropy states (gini, in our case) which can explain why it achieved a very high result. We also limited the max_depth to 3 and used a train-test split ratio of 0.4. Naïve Bayes is a probabilistic learning model and does not perform as efficiently in our case, giving an accuracy of 86.29%. The decision trees approach is more effective, which is further refined by using a Random Forest Model.
Naïve Bayes Classifiers perform better when the dataset is dynamic as it adapts swiftly to the changes whereas for a random forest approach the model needs to rebuild the forest after every change.
