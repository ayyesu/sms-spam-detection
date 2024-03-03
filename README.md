# SMS SPAM CLASSIFIER
This project, an SMS spam detector, makes use of natural language processing methods with the scikit-learn and nltk libraries from Python.
The software assesses whether or not SMS is spam by analyzing its content. 
The Pandas package is also utilized by the project for preprocessing and data manipulation.

!['header'](/images/doc_header.jpg)

# Confusion Matrix
!['confusion matrix'](/images/lgbm_classifier.png)

### Here is a more detailed breakdown of the confusion matrix:
* True label 0: This row represents the data points that actually belong to class 0.
* Predicted label 0: This column represents the number of data points that were predicted to belong to class 0. The value in this cell is 965, which means that the classification algorithm correctly predicted the label of 965 data points that actually belong to class 0.
* Predicted label 1: This column represents the number of data points that were predicted to belong to class 1. The value in this cell is 0, which means that the classification algorithm did not incorrectly predict any data points from class 0 to belong to class 1.
* True label 1: This row represents the data points that actually belong to class 1.
* Predicted label 0: This column represents the number of data points that were predicted to belong to class 0. The value in this cell is 12, which means that the classification algorithm incorrectly predicted the label of 12 data points that actually belong to class 1.
* Predicted label 1: This column represents the number of data points that were predicted to belong to class 1. The value in this cell is 137, which means that the classification algorithm correctly predicted the label of 137 data points that actually belong to class 1.


Overall, the confusion matrix shows that the classification algorithm performed very well on the data set. The algorithm made no mistakes on the data points from class 0, and it only made a few mistakes on the data points from class 1.
