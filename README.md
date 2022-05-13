# Neural_Network_Charity_Analysis
## Overview:
Using the charity data csv file provided by Alphabet Soup business, we will help create a binary classifier that is capable of predicting whether applicants that received funding will be successful if funded by Alphabet Soup.

## Results:
- Data Preprocessing
  - What variable(s) are considered the target(s) for your model? 
    The target for our model is focused on the "Is_Successful" column.
    
  - What variable(s) are considered to be the features for your model?
    Columns labeled:
    "APPLICATION_TYPE,	
    AFFILIATION,	
    CLASSIFICATION,	
    USE_CASE,	
    ORGANIZATION,	
    STATUS,	
    INCOME_AMT,                                    
    SPECIAL_CONSIDERATIONS,	
    ASK_AMT	IS_SUCCESSFUL"

  - What variable(s) are neither targets nor features, and should be removed from the input data?
    The columns labeled "NAME" and "EIN" have been removed from the dataset.
    
- Compiling, Training, and Evaluating the Model
  - How many neurons, layers, and activation functions did you select for your neural network model, and why?
    In the original model below were the amount of neurons, layers and activation functions that I used.
    ![image](https://user-images.githubusercontent.com/96352427/168401192-799f50e1-b275-4f4b-be11-199784bb6ac9.png)
    
    In the optimized model below were the amount of neurons, layers and activation functions.
    ![image](https://user-images.githubusercontent.com/96352427/168401275-183da25e-54f0-4439-939d-6f463213f541.png)

  - Were you able to achieve the target model performance? 
    In the original model, I was able to achieve 68% accuracy, however, in the optimized model, I was able to increase       the accuracy to 72%.
    
  - What steps did you take to try and increase model performance?
    I adjusted the amount of neurons for each layer, added more layerse and changed the activation functions.
    
## Summary:
Although it did not reach the 75% or higher accuracy rate, the optimized model did increase than the original model by 5% with the changes in activation functions, neurons and layers. Another option to use could be the RandomForestClassfier model, this could increase the accuracy rate. 
    
