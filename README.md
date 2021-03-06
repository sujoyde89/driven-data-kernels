### driven-data-kernels
Solution codes for drivendata.org machine learning competitions listed below

#### 1. Deng AI.ipynb - Solution code for Deng AI: Predicting Disease Spread  
This is the link of the competition https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/. The dataset for the competition can be found in the link.  
#### Problem Statement  
This problem requires us to predict the number of dengue cases each week (in each location) based on environmental variables 
describing changes in temperature, precipitation, vegetation, and more.

It is a regression problem. The metric that the competition is using to evaluate the model is mean absolute error. For more information on this metric please visit this link https://en.wikipedia.org/wiki/Mean_absolute_error.  
#### Models used  
1. Random Forest
2. Linear regression
3. Lasso Regression
4. Ridge regression

#### 2. Predict Blood donations.ipynb - Warm Up: Predict Blood Donations
This is the link of the competition https://www.drivendata.org/competitions/2/warm-up-predict-blood-donations/. The datasets for the competition can be found in the link.  
#### Problem Statement
The problem requires us to predict whether a donor will make a blood donation based on the features that are available in our dataset.

It is a classification problem. The metric that the competition is using to evaluate the model is log loss. For more information on this metric please visit this link https://www.kaggle.com/wiki/LogLoss

#### Models used  
1. Random Forest
2. Logistic regression
3. K-nearest neighbors
4. Gaussian Naive Bayes

#### 3. Pump it up.ipynb - Pump it Up: Data Mining the Water Table
This is the link of the competition https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/. The datasets for the competition can be found in the link.  
#### Problem Statement
Using data from Taarifa and the Tanzanian Ministry of Water, we will have to  predict which pumps are functional, which need some repairs,
and which don't work at all?  We will have to predict one of these three classes based on a number of variables about what kind of pump 
is operating, when it was installed, and how it is managed. 
A smart understanding of which waterpoints will fail can improve maintenance operations and ensure that clean, potable water is available 
to communities across Tanzania.  

It is a classification problem. The metric that the competition is using to evaluate the model is accuracy. Accuracy is the number of correct classification of samples to the total number of samples.

#### Models used  
1. Random Forest
2. Logistic regression
3. K-nearest neighbors
4. Gaussian Naive Bayes

#### Motivation
Here the primary reason for doing these competitions are to test our machine learning skills. 
We will not try to climb the leaderboards in the competitions rather we will just use them for practice

#### Dependencies
1. Python 3+
2. Sklearn
3. Pandas
4. Numpy
5. Xgboost
6. Matplotlib
