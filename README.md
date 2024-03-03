# SMS SPAM CLASSIFIER
This project, an SMS spam detector, makes use of natural language processing methods with the scikit-learn and nltk libraries from Python.
The software assesses whether or not SMS is spam by analyzing its content. 
The Pandas package is also utilized by the project for preprocessing and data manipulation.

!['header'](/images/doc_header.jpg)

# Confusion Matrix
!['confusion matrix'](/images/lgbm_classifier.png)

### Here is a more detailed breakdown of the confusion matrix:
- 0 represents ham (not spam) & 1 represents spam

* True label 0 Vs Predicted label 0: This row represents the data points that actually belong to class 0(not spam). The model predicted 965 data points that actually belonged to class `not spam` on the test data whiles it got 12 `not spam` data points wrong
  
* True label 1 Vs Predicted label 1: This column represents the number of data points that were predicted to belong to class 1 (spam). The model predicted 137 data points that actually belonged to class `spam` on the test data whiles it got 1 `spam` data point wrong


Overall, the confusion matrix shows that the classification algorithm performed very well on the data set. The algorithm made fare mistakes on the data points from class 0 (not spam), and it only made one mistake on the data points from class 1 (spam).
