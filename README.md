# Credit_Card_Fraud_Detection
This project centers on the application of a Random Forest classification model for the identification of fraudulent credit card transactions. The project employs a dataset available at a specified link.

<img src="Image\Manhattan_and_Brooklyn_bridges.jpg">

__About Dataset__: This dataset documents credit card transactions carried out by European cardholders in September 2013 over a two-day period. The dataset encompasses 284,807 transactions, of which 492 are identified as fraudulent, making up only 0.172% of all transactions. The dataset primarily comprises numerical variables derived from PCA transformation, in addition to features like 'Time,' 'Amount,' and the binary 'Class' variable indicating fraud (1) or non-fraud (0). The original features and background data are undisclosed for confidentiality reasons.

The project began by importing the required libraries, proceeding to read and store the credit card transaction dataset. Data analysis involved the identification of missing values and the recognition of a substantial class imbalance issue, with only 0.172% of transactions flagged as fraudulent. To address this challenge, a Random Forest classification model was employed, with a focus on the f1 score as the primary evaluation metric due to the dataset's imbalance. Hyperparameter tuning was carried out to enhance model performance. The project reported an accuracy of 0.836 for the training set and 0.845 for the test set, and concluded by examining the confusion matrix for a comprehensive assessment of the model's performance in identifying fraudulent transactions.

<img src="Image\Manhattan_and_Brooklyn_bridges.jpg">
