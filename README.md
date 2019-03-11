# TimeSeriesClassification
About Dataset
The dataset contains 7 folders that represent seven types of activities. In
each folder, there are multiple files each of which represents an instant of a human
performing an activity. Each file containis 6 time series collected from activities
of the same person, which are called avg rss12, var rss12, avg rss13, var rss13,
vg rss23, and ar rss23. There are 88 instances in the dataset, each of which contains
6 time series and each time series has 480 consecutive values.
Keep datasets 1 and 2 in folders bending1 and bending 2, as well as datasets 1,
2, and 3 in other folders as test data and other datasets as train data.

Feature Extraction
i. Research what types of time-domain features are usually used in time series
classification and list them (examples are minimum, maximum, mean, etc).
ii. Extract the time-domain features minimum, maximum, mean, median, standard
deviation, first quartile, and third quartile for all of the 6 time series
in each instance.
iii. Estimate the standard deviation of each of the time-domain features you
extracted from the data. Then, use Python's bootstrapped or any other
method to build a 90% bootsrap confidence interval for the standard deviation
of each feature.
iv. Use your judgement to select the three most important time-domain features

BINARY CLASSIFICATION USING LOGISTIC REGRESSION
  Break each time series in your training set into two (approximately) equal length time series. Now instead of 6 time series for each of the 88 instances,
  you have 12 time series for each instance.
  Calculate the p-values for your logistic regression parameters and refit a logistic regression model using your pruned set of features.
  Performed Recursive Feature Elimination and 5-fold Cross Validation to determine best value of l.
  
 BINARY CLASSIFICATION USING L1-PENALIZED LOGISTIC REGRESSION                                                                                MULTI-CLASS CLASSIFICATION
  Build an L1-penalized multinomial regression model to classify all activities in your training set.
  

  
