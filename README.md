# Predicting-Boston-House-Pricing
The objective of this project is to build a model that predicts the price of a home in the suburbs of Boston, Massachusetts.

The Boston housing data was collected in 1978 and each of the 506 entries represent aggregated data about 14 features for homes from various suburbs in Boston, Massachusetts. For the purposes of this project, the following preprocessing steps have been made to the dataset:
 * 16 data points have an 'MEDV' value of 50.0. These data points likely contain missing or censored values and have been removed.
 * 1 data point has an 'RM' value of 8.78. This data point can be considered an outlier and has been removed.
 * The features 'RM', 'LSTAT', 'PTRATIO', and 'MEDV' are essential. The remaining non-relevant features have been excluded.
 * The feature 'MEDV' has been multiplicatively scaled to account for 35 years of market inflation.
