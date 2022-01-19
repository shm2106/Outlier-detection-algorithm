# Outlier-detection-algorithm
Aim:To build an outlier detection algorithm within 1 week of receiving this assignmentfor the provided data set.

Given:The data consists of values of a variable observed every minute every minute over a period of 1 week.The training set is the data for the first 6 days and
the test set is the last day data.

Methods used:
1)Box plot(Taking the unique variable only once)
2)Threshold outlier value determination using the frequency of variables.(Aftere observing the data plot and seeing the boxplot which seems to have neglected some anomalous values ) 
3)Mean of the non-0 variables to determine the range(+/-mean) for threshold determination.(This can be thought of a signal data where the values hover about the mean value)
