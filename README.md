# Neural_Network_Charity_Analysis- Module 19 Challenge
---
Neural Network model the optimizing of the data.

## Overview 
---
Utilizing my knowledge of machine learning and neural networks we will take the data provided to us from Alphabet Soups team, and create a prediction as to those applicants most likely to be successful if funded by Alphabet Soup. We will do those through cleaning the data and testing the data in multiple ways to get as close as we can to an accuracy of 75%.

## Results
---
# Data Preprocessing

    - What variable(s) are considered the target(s) for your model?
        -- Any of the loans that are marked as "Is Successful" is a target of the model as they are the funded loans
        
    - What variable(s) are considered to be the features for your model 
        -- The column "Is Successful is the feature for this model
        
    - What variable(s) are neither targets nor features, and should be removed from the input data?
        -- The variable that could be removed are "Ein and Name" as they do not add any help or accuracy to the model.

# Compiling, Training, and Evaluating the Model

    - How many neurons, layers, and activation functions did you select for your neural network model, and why?
        -- I started with 80, 30 and 1 with 2 layers. Then tried to optimized to 100, 80, 60, 40 but could not get any better than 
           an accuracy of 72.63%                 
                           
![CTEM.png](https://github.com/Normanfamdamly/Neural_Network_Charity_Analysis/blob/main/Images/CTEM.png)

    - Were you able to achieve the target model performance?
        -- I was not able to achieve a 75% accuracy. I could only get to 72.63%![Opy3.png](.
        
    - What steps did you take to try and increase model performance?
        -- I made changes to the model by adding more hidden layers and changing the number epochs and changing the neurons in            the layers, but nothing got me closer than 72.63%
        
![Opt3.png](https://github.com/Normanfamdamly/Neural_Network_Charity_Analysis/blob/main/Images/Opt3.png)        

## Summary
---
The model accuracy ended with 72.63%.  The goal of the work was to utilize the data set and predict if the loan project would be successful.  I was unable to be successful in getting us to a 75% accuracy rate with the data we had.  Maybe we could have dropped a few of the features of the data and could have made it more effective in the training and got us closer.
