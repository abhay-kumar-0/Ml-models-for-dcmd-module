# Ml-models-for-dcmd-module
Machine learning models for performance prediction of direct contact membrane distillation module.


we consider three different types of machine-learning models. These models are Linear Regression, K-Nearest Neighbor, 
and Xgboost. Every three models have four input features these are feed flow temperature, feed flow concentration, feed flow rate, 
and permeate flow temperature. Based on these features predict the permeate flux as output.

Models are created using the scikit-learn library in the Python programming language.
Use 16 experimental data sets with inputs and outputs to construct models. Four data points have been used to validate the model after it had been trained using 12 data points. For training and testing purposes in this study, we chose models that are effective for small datasets, and we tuned the hyperparameters to be appropriate for very small datasets.

This is useful for chemical researchers and in chemical industry to find that which parameters are sutiable for process.
