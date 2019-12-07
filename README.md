# London-Dataset

Working for customer analytics company.Employed techniques like decilation to discretize values.Just to experiment used tschniques like
Minimum Description Length Binning.
Used Variable Inflation Factor to check for multi collinearity and select statistically significant features.
test.
Multi-collinearity is also possible when the correlation between pairs of variables are small.
Also tried selecting best features based on chi2 
VIF values for the included variables should be less than 10
Procedure to remove multi-collinearity

get vif values + or - 10 and drop the closest feature for eacha nd every feature.
Iterate the above process till u get some features with vif values <5

Results:

The feature no 7,9,13,24,26 are useless for prediction.

The feature no 18,23,32,34,36,39 are strong for prediction and is used for modelling.

