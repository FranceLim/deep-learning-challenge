# deep-learning-challenge

## Purpose of the Analysis
The purpose of the analysis was to utilize deep learning to predict organizational success. 

## Results
Data Preprocessing
- The target variable for the model was 'IS_SUCCESFUL'.
- The features for the model included 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', and 'ASK_AMT'.
- The variables that were removed include 'EIN' and 'NAME'.

Compiling, Training, and Evaluating the Model
- For the neural network model, I utilized 80 for the first hidden layer, 30 for the second hidden layer, and 1 for the output layer for a total of 111. I utilized three layers. For the activation function, I utilized relu and sigmoid.

- I was not able to achieve optimization. I tried chaning the number of neurons, added additional layers, changed the activation function to tanh, and increase the number of epochs. However, none of those variances resulted in an accuracy rating of over 0.75.  

## Summary
The model resulted in an accuracy rating of 0.7233 with a lof of 0.5734, which is not ideal. The Random Forest model may be another model to utilize for this data set. The Random Forest model algorithm, with it's multiple decision trees, may be an alternative model to improve accuracy. 
