# Company-Bankruptcy-Prediction
The project will predict whether the company is going to be Bankrupt

Predicting the financial health of companies and firms has become one of the key interests for their owners, creditors and all the stakeholders alike, especially now when huge amounts of financial data can be stored and analysed on computers.

The purpose of such a predictive model which tries to foreseee the bankruptcy is to combine various econometric parameters that can effectively guage the financial state of a company and enable the management to take pre-emptive measures that can potentially help to avoid any financial distress to the company.

In this project we present our analysis of the data at hand as we go on selecting various subsets of the huge feature space available to us. We try to compile and compare each and every result as we step from a niave modelling to a more nuanced and standard one. We have employed some of the most widely used classification algorithms for this project namely:

    Logistic Regression
    SVM
    KNN
    XGBoost
    Gaussian Naive Baye's
    Random Forest



Conclusion:

    If Accuracy is critical to the use case, then the KNN model should be used along with feature selection, to obtain a 96.6% Accuracy score.
    If Recall is critical to the use case, then the Gaussian Naive Bayes model should be used with feature selection and SMOTEENN, to obtain an 88.6% Recall value.
    If overall performance is critical to the use case, then KNN  Model with, feature selection(RandomForest & Isolation forest) and SMOTE ENN can be used to obtain an F1 score of 33%.
