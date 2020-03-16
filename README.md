### Credit-Card-Fraud-Detection

   With an abundant growth in the credit card transactions, credit card fraud has
become progressively extensive. In this, the credit card fraud detection is done by
identifying the outliers with help of multiple features such as time, amount, location,
merchant type, etc. The fraud is detected by analyzing the spending behaviour of the
cardholder.
   Used Random Forest for Outlier detection and measuref the result of detection model using Precision-Recall technique. We have also handle Imbalanced data using SMOTE (Synthetic Minority Over-sampling Technique ) to increase accuracy and efficiency of detection model.
   Behavioural pattern of spending money depends on past history of transactions and attributes such as location, daily expenses, transaction time of cardholder can be compared with current transaction details to detection credit card frauds. Deviation from such behavior helps to detect fraud with more accuracy. With the deviation in behavioral data, we used different data mining techniques to detect the fraud. The model can then be used to identify whether the new transaction is fraud or not.

#### Installation
   - Download dataset https://www.kaggle.com/mlg-ulb/creditcardfraud/download

#### Objective

 - To detect fraudulent transactions by considering customer past behavioral data.
 - It identifies the frauds with good accuracy and hence the number of wrong classifications should be minimum.
 - It should be able to detect the fraud while it is in transit and alert the customer as soon as possible.
 - It should not term any genuine transaction as fraudulent.

#### Algorithms

  - K- nearest neighbours
  - Decision Tree
  - Random Forest
  
#### Results

              -----------------------------------------------------------
              | Algorithms           | Area Under ROC Curve | F1 Score  | 
              -----------------------------------------------------------
              | K-Nearest Neighbor   |    0.7445            | 0.9746    |
              ----------------------------------------------------------- 
              | Decision Tree        |    0.9149            | 0.9982    |
              ----------------------------------------------------------- 
              | Random Forest        |    0.9157            |  0.9994   |
              ----------------------------------------------------------- 

#### Conclusion
  - We obtained fairly well accuracy in all the three classifier algorithms
  - The working of KNN, Random Forest and Decision Tree was acknowledged
  - More attention needs to be given on the fraudulent data, which is much less than the correct one and which is overseen
  - Different methods such as location tracking of card-holder and matching with past locations fetched from the database. 
