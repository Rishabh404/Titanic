# Titanic

In this project, I have attempted to predict the survival of passengers in Titanic based on the passenger attributes mentioned in the 
dataset like Age, Gender, Number of Siblings onboard, Fare etc. I have used two machine learning models to predict which passengers were 
likely to survive the sinking and which were not.

1. XgBoost:
   This machine learning method was able to achieve almost 83% accuracy on the predicted values.
   
2. Random Forest:
   This machine learning model performed the best out of the two implemented, achieving almost 90% accuracy. The missing values before the
   model implementation were handled as follows:
   
   For the Age column, missing values were filled with the mean of the other Age values. This took place in both training and test data.
   For the Fare column in test Data, there was one missing value which belonged to passenger class 3. This value was imputed by taking the
   median of all the remaining fare values belonging to the same fare class 3.
