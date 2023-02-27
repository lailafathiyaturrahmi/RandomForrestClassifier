# Random Forrest Classifier

The project contains data cleansing where I prep data until it's ready for analysis. After cleaning the data I did an exploration to get more information from the data. Based on my exploration, I found that the longer a customer subscribes, the smaller the proportion of churn that occurs. Finally, modeling with three conditions, firstly without imbalance data handling, secondly handling with oversampling, and handling with undersampling.

The best random forest classifier is provided by random forest with oversampling to overcome unbalanced data. I came to this conclusion by looking at evaluation metrics. The big difference between the model without handling the imbalanced data and treating it with oversampling is in the in recall score, where handling the imbalance increases the recall score from 46% to 95%. This means that the data imbalance makes predictions bias to the major category, so the churn predictions are less than no churn and give wrong predictions.

