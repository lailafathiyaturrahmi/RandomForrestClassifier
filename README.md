# Random Forrest Classifier

a company needs to know the prediction of customer churn. Information about which customers are potentially churn can give companies advice on how to treat customers to prevent them from churning. Customer churn prediction can be built using several methods such as random forest classifier. Classification methods in machine learning can be affected by data balance conditions. Data with unbalanced target variable categories will make the classification more inclined to the majority category so imbalance data needs to be balanced first.

The project contains data cleansing where I prep data until it's ready for analysis. After cleaning the data I did an exploration to get more information from the data. Based on my exploration, I found that the longer a customer subscribes, the smaller the proportion of churn that occurs. Finally, modeling with three conditions, firstly without imbalance data handling, secondly handling with oversampling, and handling with undersampling.

The best random forest classifier is provided by random forest with oversampling to overcome unbalanced data. I came to this conclusion by looking at evaluation metrics. The big difference between the model without handling the imbalanced data and treating it with oversampling is in the in recall score, where handling the imbalance increases the recall score from 46% to 95%. This means that the data imbalance makes predictions bias to the major category, so the churn predictions are less than no churn and give wrong predictions.

