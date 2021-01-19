# Classification

The purpose of this assignment is to figure out the credit quality of borrowers by alternative means versus the conventional A-lender (ex: Big Five Banks in Canada) standards.

Observations from the credit_risk_resampling.ipynb file in the Starter_Code directory:

1. The SMOTE Oversampling yields the best balanced accuracy score of 0.9936781215845847.
2. The Naive Oversampling, SMOTE Oversampling, and SMOTEENN models yield the best recall score of 0.99.
3. The Naive Oversampling, SMOTE Oversampling, Undersampling, and SMOTEENN models yield the best geometric mean score of 0.99.

Observations from the credit_risk_ensemble.ipynb file in the Starter_Code directory:

1. The Easy Ensemble Classifier model yields the best balanced accuracy score of 0.9931452145768567.
2. Both Balanced Random Forest Classifier and Easy Ensemble Classifier model yield the best recall score of 0.99.
3. Both Balanced Random Forest Classifier and Easy Ensemble Classifier model yield the best geometric mean score of 0.99.
4. The top three features to predict borrower risk are: derogatory marks, loan size, and interest rate.