# deep-learning-challenge
* This is the module 21 assignment for bootcamp, which focuses on machine learning and neural networks. 

## Overview
* The purpose of this analysis is to determine whether or not an applicant will be successful if funding is granted from Alphabet Soup.

## Results
* Data Preprocessing:
    * The target variable for this model is 'IS_SUCCESFUL'
    * The feature variable are the following: 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS',             'INCOME_AMT', 'SPECIAL_CONSIDERATIONS' and 'ASK_AMT'.
    * There are two variable that were removed because they did not add to the model. They are 'EIN' and 'NAME'.
    
* Compiling, Training, and Evaluating the Model:
    * Buidling the model is a process of experimentation. To start out, I chose to start out with 2 hidden layers followed by an output layer.       There are different choices available to activate the model, I chose to use 3 different options, 'relu', 'tanh' and 'sigmoid'.
    * The target for the optimized model was 75 percent accurate. My optimized model has an accuracy of 73.00%. 
    * To optimize the model, I tried 3 different steps. The first was to change the activation function. Step two was to adjust the number of       neurons in the hidden layers. The final step was to reduce the number of epochs to the training regimen. 
    
* Summary:
    Overall, this model has an accuracy of 73%. In some instances, 73 percent may be good enough, but in this case, I believe that a different model could be more effective. Here we used a neural network model, which has both strengths and weaknesses. One particular strength of a neural network model is that it is useful for tasks like image or speech recognition. I think that a random forest model could be interesting with this data. This dataset seems to relatively simple, with a mix of numerical and categorical data, which is why I suggest trying a random forest model.