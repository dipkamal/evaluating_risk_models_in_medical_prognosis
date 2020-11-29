
# Evaluating Risk Models

We'll build a risk score model for retinopathy in diabetes patients using logistic regression.
  
## Diabetic Retinopathy
Retinopathy is an eye condition that causes changes to the blood vessels in the part of the eye called the retina.
This often leads to vision changes or blindness. Diabetic patients are known to be at high risk for retinopathy. 
    
## Logistic Regression    
Logistic regression is an appropriate analysis to use for predicting the probability of a binary outcome. In our case, this would be the probability of having or not having diabetic retinopathy.
Logistic Regression is one of the most commonly used algorithms for binary classification. It is used to find the best fitting model to describe the relationship between a set of features (also referred to as input, 
independent, predictor, or explanatory variables) and a binary outcome label (also referred to as an output, dependent, or response variable). Logistic regression has the property that the output prediction is always 
in the range [0,1]. Sometimes this output is used to represent a probability from 0%-100%, but for straight binary classification, the output is converted to either 0 or 1 depending on whether it is below or above a certain threshold, usually $0.5$.