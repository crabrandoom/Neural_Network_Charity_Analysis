# Neural_Network_Charity_Analysis

## Overview

A CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years is being analyzed in order to work to help the foundation predict where to make investments.

## Results

### Data Preprocessing
    -What variable(s) are considered the target(s) for your model?
   
    IS_SUCCESSFUL
    
   -What variable(s) are considered to be the features for your model?
    
    'ASK_AMT','CLASSIFICATION','INCOME_AMT','APPLICATION_TYPE', 'NAME'
    
   -What variable(s) are neither targets nor features, and should be removed from the input data?
   
    AFFILIATION                   
    USE_CASE                      
    ORGANIZATION                  
    STATUS                        
    SPECIAL_CONSIDERATIONS        


### Compiling, Training, and Evaluating the Model

   -How many neurons, layers, and activation functions did you select for your neural network model, and why?
  
        3 hidden layers that used relu, and the outer layer used Sigmoid
  
   -Were you able to achieve the target model performance?
   
        Yes
  
   -What steps did you take to try and increase model performance?
   
        I added an extra hidden layer and then added another categorical variable that was initially discarded
  
## Summary

Applicant is 80% likely to be successful if their name appears more than 5 times. Intially the NAME category was dropped but when added and properly binned accuracy improved dramatically.
