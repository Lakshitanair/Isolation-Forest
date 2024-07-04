# Isolation-Forest
Isolation Forest is an algorithm designed for anomaly detection. It isolates observations by randomly selecting a feature and then randomly selecting a split value between the maximum and minimum values of the selected feature. Anomalies are the points that are easier to isolate and have shorter paths in the trees compared to normal points.

Tips:
Applying this unsupervised algorithm for anomaly detection on ‘tips’ dataset allows us to 
find observations that are significantly different from the rest of the data. These differences 
might represent unusual or unexpected behaviour in the context of restaurant bills and tips.


Email Spam:
Using .predict() function we are able to identify the outliers and label them as -1 whereas the 
others as 1.This helps us to find out the anomality in the given dataset. This code 
demonstrates how to use the Isolation Forest algorithm for anomaly detection on the dataset
and identifies the spam mails present in the dataset

