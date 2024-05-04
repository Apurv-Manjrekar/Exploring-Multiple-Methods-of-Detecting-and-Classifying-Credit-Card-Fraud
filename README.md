# Exploring-Multiple-Methods-of-Detecting-and-Classifying-Credit-Card-Fraud
Attempting to identify fraudulent activity in the realm of financial transactions is becoming increasingly more important as online and contactless methods of payment are more prevalent. Utilizing a dataset that included European cardholders in a two day period in 2013, models were created in order to identify trends and patterns that surround credit card fraud. Initial findings indicated that Logistic Regression performed the poorest on the base data, while the Decision Tree Model performed well with the highest recall. After undergoing undersampling, the Gradient Boosting Model performed the best. Oversampling also led to improvements in recall scores, with Logistic Regression showing good parity with Gradient Boosting. After PCA reduction was applied to the Gradient Boosting Model, training times were able to be reduced without affecting recall scores. This sets up for future improvements where more advanced techniques can be employed to handle imbalance data. This will further enhance the precision and efficiency of credit card fraud detection models.
