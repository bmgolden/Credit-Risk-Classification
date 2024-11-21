# Credit-Risk-Classification
Supervised Learning Module HW

Overview 

The principal purpose of this analysis is to help a financial institution classify potential borrowers as either low-risk, healthy, high-risk, not healthy when deciding on the loan parameters or whether they will offer a loan or not to prospective debtors. The financial institution will determine whether to implement this model based on factors that are calculated in the confusion matrix and classification report and how the model performs after training and testing the model. This model is based on Logistic Regression as it is very permeable and interpretable in situations such as this when the outcome is categorized by binary classification. The financial institution aims to utilize this basic model in hopes of mitigating potential financial losses and aiding in making smart financial decisions going forward. 

Results 

After conducting the linear classification regression and visualizing the confusion matrix and classification report hear are the summary statistics and performance metrics and what they mean analytically. 

Confusion Matrix

The main purpose of the confusion matrix is to help outline and visualize the number of true positives, true negatives, false positives, and false negatives. According to the confusion matrix, based on the test data, there are 18655 true positives, 110 false positives, 36 false negatives, and 583 true positives, all of which are more detailed in the classification report. 

Classification Report

•	Accuracy Score: According to the classification report the accuracy score is 99%, meaning that the model correctly predicts almost 100% of all the loans in the test dataset. 

•	Precision: For healthy loans the precision is 100%, meaning that all of the loans that were classified as healthy loans are healthy, while the accuracy score for high-risk loans is 84%, meaning that some loans that were classified as high-risk are healthy, which overall is sufficient performance. 

•	Recall: The recall for healthy loans is 99% meaning that the model identified almost all healthy loans, but some were missed as they were false negatives. A recall score of 94% for high-risk loans is a strong number, but it does mean that some false negatives were once again misclassified as those loans should have been classified as healthy.

•	F1-Score: The f1-score for healthy loans is 100%, and for high-risk it is 89%. 

•	Overall: For the model wholistically,  the accuracy is 99%, the precision is 92%, the recall is 97%, and the F1-Score is 94%. 

Summary

Overall, taking into consideration the model and all of its metrics individually, the model performs extremely well. The logistic regression was used correctly in binary classification when trying to influence decisions classifying loans as non-risk or high-risk when examining a multitude of factors such as borrower rate, borrower income, debt to income, number of accounts, loan size, total debt, and derogatory marks. The model performs very well for each classification, providing near-perfect performance in predicting healthy loans and solid performance in predicting high-risk loans, when considering the pertinent statistics.

Recommendation

If I were running an analysis for this institution, after implementing and investigating the results, I would strongly recommend the execution of this supervised learning model for ordering loans. The model has high accuracy, and strong recall, while being easily interpretable and effcinent, while being easy to initially employ. The model does exhibit tendencies to misclassify some healthy loans as high-risk, but proves to be very strong as not misclassifying some loans that are high-risk as healthy. I feel that this risk is acceptable as the main intention of a model such as this would be to avoid losing funds on loans that should have been classified as high-risk and were not. Some improvements could be implemented overtime, by adding more deep-learning concepts and hyperparameters. Overall, the model is acceptable and I feel should be used in helping the company make financial decisions. 
