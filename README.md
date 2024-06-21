Colab links:
-AlphabetSoupCharity_
https://colab.research.google.com/drive/1KZ1N2TwznnbwErj8pdwSAIPqvwxVF9eR

-AlphabetSoupCharity_Optimization
https://colab.research.google.com/drive/1Kj7xaWRMeUDBEPNJlY4FpOhBu2l8cBuN

# Deep-learning-challenge

Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

*From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:
*EIN and NAME—Identification columns
*APPLICATION_TYPE—Alphabet Soup application type
*AFFILIATION—Affiliated sector of industry
*CLASSIFICATION—Government organization classification
*USE_CASE—Use case for funding
*ORGANIZATION—Organization type
*STATUS—Active status
*INCOME_AMT—Income classification
*SPECIAL_CONSIDERATIONS—Special considerations for application
*ASK_AMT—Funding amount requested
*IS_SUCCESSFUL—Was the money used effectively

#### Analysis

The purpose of this report is to create a model to determine the sucess rate of the applicants seeking funding. The process helps to identify good applicants based on some features but as per the analysis requires some of them were dropped and cleaned in order to achieve the desired results. we can used our skills in machine learning along with neural networks.

### Results:

as required some data were removed in the first solution file as EIN and NAME since the other columns where important to keep and accuracy of 0.7264 was obtained.
in the second file were multiples attemtps were performed i added back the NAME column and i tested with antoher layer and different number of neurons obtaning an accuracy of 0.7313 and 0.7319 respectively.

●Data Preprocessing
  ● What variable(s) are considered the target(s) for your model?  in this model the variable targered was the successful because it indicated the clasification in this case.
  ● What variable(s) are considered to be the features for your model? the rest of the other columns in the first solution back in my second file i added back name.
  ● What variable(s) are neither targets nor features, and should be removed from the input data? i removed in both my files the EIN as it is just used for taxes purposes and it doesnt has to be with their performance.


● Compiling, Training, and Evaluating the Model
  ● How many neurons, layers, and activation functions did you select for your neural network model, and why? in my optimized file i used another layer with more neurons. 
  layers: 14,21 and 17 and the accuracy went from 0.7313 to 0.7319 (very minimal)
  ● Were you able to achieve the target model performance? i was not able to do it and i tried multiple times.
  ● What steps did you take to try and increase model performance? i added back the names and i added more layers and more neurons also i changed the layers 2 & 3  to be sigmoid and i decreased the number of epochs to 50.

### Summary: 
as you can see in my results i was not able to obtain a performance over 75%. My highest one was only 0.7319 and this is not considered very accurate and usefull. i need to explore another sources in machine learning to be able to obtain this goal eventually and help nonprofit foundations like Alphabet Soup to obtain better results. one recomendation could be to use NAive Bayes since since it is a binary classiffication algorithm used in multi-class classiffication models.
