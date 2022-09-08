# Neural_Network_Charity_Analysis

## Overview 

- I was tasked with the responsibility to use my knowledge of machine learning and neural networks to create a binary classifier that will be capable of predicting whether applicants will be successful if funded by Alphabet Soup. 

## Results

### Data Preprocessing

- What variable(s) are considered the target(s) for your model?
  - For this model the column I would consider the target would be the IS_SUCCESSFUL column.

- What variable(s) are considered to be the features for your model?
  - Other variables that can be considered to be the features for the model would be the AFFILIATION and the INCOME_AMT.

- What variable(s) are neither targets nor features, and should be removed from the input data?
  - We removed the Identification columns which are EIN and NAME because they did not alter nor suport any of the analysis done in the model.

### Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - For the main model I used 95 neurons and 65 layers with 2 hidden layers. I did this because in a previous model I build these selections worked for me so I wanted to go from there. 

- Were you able to achieve the target model performance?
 - I did not reach the target model performance. The first attempt was 53%, the second was 60% and the third was 60% again. 

- What steps did you take to try and increase model performance?
  - I tried to increase the model performance by playing around with the amount of nuerons, layers and hidden layers. I tried removing hidden layers, increasing nuerons as well as decreasing neurons to see what would give me the best results. 

## Summary
  - My original model had an accuracy score of 66%, through optimization, I actually failed miserably and brought it down to 53% and 60%. In the future I will increase the Neurons and keep about 3 hidden layers. That seemed to be the sweet spot for the 66% However i did not hit the target of 75%. 
  - My recommendation for a different model would be to change up the classifiers to hopefully optimize the model better. 

