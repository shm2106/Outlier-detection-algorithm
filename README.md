# Outlier-detection-algorithm
Aim:To build an outlier detection algorithm for the provided data set.

Given:The data consists of values of a variable observed every minute every minute over a period of 1 week.The training set is the data for the first 6 days and
the test set is the last day data.

Methods used:

1)Box plot(Taking the distinct variable values only once)

2)Threshold outlier value determination using the frequency of variables.(After observing the data plot and the boxplot which seems to have neglected some anomalous values ) 

3)Mean of the non-0 variables to determine the range(+/-mean) for threshold determination.(This can be thought of as a signal data where the values hovers around the mean value)
