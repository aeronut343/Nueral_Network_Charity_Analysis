# Nueral_Network_Charity_Analysis

# Overview
This analysis seeks to develope a neural network model that will predict whether or not a company called "Alphabet Soup" should fund certain endeavors based on past data. 

# Results
## Data Preprocessing
- The target variable for the model was SUCCESSFUL, which determined whether or not the investment was considered successful
- The features considered included the amount of money requested, the income of the company making the request, the type of company and their affiliation, the applicants classification, and the type of application
- The variables which were immediately removed as irrelevant were the unique ID of the application and the name of the applicant

## Compiling, Training, and Evaluating the Model
- Through trial and error I decided on 4 hidden layers of 12 nodes each, using the 'relu' activation function
- I was not able to achieve the target accuracy of 75%, but got up to 63% which was better than the initial accuracy of 53%
- To increase the performance of the initial model I added more hidden layers and nodes, experimented with the activation functions, altered some categorical buckets to balance out the data, and changed the number of epochs that the model trained on

# Summary
This neural network was unable to achieve the desired accuracy, though it's possible that some more preprocessing and a better understanding of the business application could improve the model further. Other models such as a random forest model may be better for this application, and at the least help understand which pieces of data are possibly skewing the predictions while offering similar results and a less resource intensive approach. 
