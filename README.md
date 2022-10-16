# Bank-Marketing-Effectiveness-Prediction

Problem Statement == { The data is related to a Portuguese banking institution’s direct marketing campaigns (phone calls). 

The marketing campaigns were based on phone calls. 

Often, more than one contact with the same client was required, to access if the product (bank term deposit) would be (‘yes’) or not (‘no’) subscribed. 

The classification goal is to predict if the client will subscribe to a term deposit (Result variable - y). }


Steps carried out for our analysis == { Data Overview,
                                        Pre Processing Data,
                                        Exploratory Data Analysis
                                            a) Univariate
                                            b) Bivariate,
                                        Feature Engineering,
                                        Handling Class Imbalance (SMOTE),
                                        Machine Learning Model Implementation(Naive Bayes, KNN, SVM, Random Forest, XGboost),
                                        AUROC and ROC Curve. }


We have implemented different machine learning models to predict whether people have subscribed to a term deposit or not. From the evaluation metrics of the different models, we came to the conclusion that the accuracy of the XG boost ensemble model is the highest compared to the remaining models i.e Accuracy: 0.9318026585404298 is achieved.
Thus the best model is the XG boost ensemble and hence we tend to apply hyperparameter tuning and cross-validation for the same.

