# Bias-Variance Trade-off

[reference][bias-variance]

A typical supervise learning method will have three types of errors: 

* Bias error
* Variance error
* Irreducible error

High bias makes learning faster and easier to understand, but less flexibility and less predictive performance.

High bias algorithms: linear regression, linear discriminant analysis, logistic regression.

Low bias algorithms: decision tree, k-NN, SVM, NN

Variance means the amount of estimate changes given different training dataset.

Generally, non-parametric machine learning algorithm (e.g. decision tree) have a high variance.

High variance algorithms: decision tree, k-NN, SVM

Low bias algorithms: linear regression, linear discriminant analysis, logistic regression.

Usually, increase bias => decrese variance and vice versa.

[bias-variance]: https://machinelearningmastery.com/gentle-introduction-to-the-bias-variance-trade-off-in-machine-learning/