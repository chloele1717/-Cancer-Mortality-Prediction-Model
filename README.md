# Cancer-Mortality-Prediction-Model: Created a cancer mortality prediction model based on US census data from 2010 to 2016.
The goal of the project is to identify the relationship between the various features 
and the target variable, which is the death rate due to cancer in different regions in 
the US. The model aims to predict the death rate based on the available features 
such as average annual count of cancer cases, median age, poverty percentage, 
population estimates, and others.

The results of the model can be used by the business to make informed decisions on 
the allocation of resources, developing public awareness campaigns, and identifying 
areas where medical intervention is required. Accurate results from the model will 
help the business, public health officials and government to make informed decisions 
and target interventions effectively. People living in these areas will benefit from 
these interventions, and their overall health and well-being will improve.
On the other hand, incorrect results can cause businesses to invest in the wrong 
areas or public health officials to implement ineffective interventions. This can result 
in wasted resources, increased costs, and potentially negative outcomes for the 
people living in these areas. 

The expected outcome of the experiment is a linear regression model that best fits 
the data points of the given features with “TARGET_deathRate”. The goal of the 
model is to minimize the mean squared error between the actual values and the 
predicted values.

Multivariate linear regression model with some feature engineering and three
regularization techniques will be applied to improve the performance of a machine 
learning model, and also to make sure that we can get the best possible 
performance result. 

The training dataset has 2438 rows and 35 columns while the testing dataset has 
609 rows and 35 columns. Based on the summary of the training and testing sets, 
there are 3 columns with missing values that need further exploration and cleaning: 
“PctSomeCol18_24”, “PctEmployed16_Over” and “PctPrivateCoverageAlone”.
Additionally, there are two categorical variables named “binnedInc” and “Geography”
that need to be transformed into numerical variables in order to be fit in the linear 
regression model. Based on the descriptive statistics of both datasets, 
“avgAnnCount”, “avgDeathsPerYear” and “popEst2015” are the three features that 
have large ranges between their min and max values, which might require scaling
method to bring the values to similar range

## Dataset:

Training set: https://drive.google.com/file/d/1qe5KgjJrITsw1h8t-fJhqJw2DMtcfaW5/view
Testing set: https://drive.google.com/file/d/1OT6Y7TXT4c630XPKrl-uh3DmcSOpOypq/view
