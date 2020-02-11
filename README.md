# Spanish-High-Speed-Rail-tickets-pricing---Renfe

## Summary
We use learning curve to compare the models, the learning curve of learning regression is underfitting and the learning curve of Gradient Boosting regression is overfitting. As a result, The best model is Random Forest Regression and the parameter is n_estimators = 100. However, this is not the best one. First, in the preprocessing, we can change the feature of origin and destination to value of distances. Also, in order to decrease more features, we can compare different kinds of method of reducing dimension to obtain the best result. Second, the parameters of Random Forest are at least 6 different kinds of parameter, but we only choose one parameter. Thus, we still need to find the best parameter.


## Skill
Python: Pandas, Numpy, scikit-learn, matplotlib, learning curve
