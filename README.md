# PROJECT-PROPOSAL-SCREENING-

About the Project: DonorsChoose.org posts classroom project proposals for raising funds. Objective is to automate screening process by building a model to predict whether a proposal will be approved for posting on website or not.


Data Analysis: Dataset is a combination of Categorical, Numerical and Text features. Used BoW and TF-IDF for featurization of the text data.


Modelling Strategy: Chose Logistic Regression, Naive Bayes and KNN for modelling the data. Applied k-fold Cross Validation for each algorithm to choose best Hyperparameter values.


Performance: Accuracy, AUC and F1 scores were chosen as Performance metrics. Naive Bayes model returned the best AUC score of 0.69 and F1 score of 0.85
