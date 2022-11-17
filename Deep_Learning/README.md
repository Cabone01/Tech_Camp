# Charity Funding Predictor
Here we were given a dataset by a nonprofit foundation called Alphabet Soup. The goal was to be able to create a model that could accurately predict that if an applicant is funded, it is successful. The dataset had the following variables when it was given to us.  
* EIN - Identification column
* NAME - Identification column
* APPLICATION_TYPE - Alphabet Soup application type
* AFFLICATION - Affiliated sector of industry
* CLASSIFICATION - Government organization classification
* USE_CASE - Use case for funding
* ORGANIZATION - Organization type
* STATUS - Active status
* INCOME_AMT - Income classification
* SPECIAL CONSIDERATIONS - Special consideration for application
* ASK_AMT - Funding amount requested
* IS_SUCCESSFUL - Was the money used effectively    
## Creating the Model
The variable that was chosen as the target was IS_SUCCESSFUL since the whole purpose of the model was to find successful outcomes. The ones that were ignored in the model were EIN, NAME, STATUS, and SPECIAL_CONSIDERATIONS.          
When making the model, it was decided to add three hidden layers to increase the accuracy of the model. ReLU was used for the activation functions because it is believed to be more effective than Sigmoid and Tehn.         
![image](https://user-images.githubusercontent.com/89541481/202514786-bda65e60-4181-40f9-996a-5177700afb0e.png)     
## Results
As you can see below, managed to end with an accuracy of about 73%. Even though the improvements were minimal what was changed was that the hidden nodes were increased slightly by about 20. Then the batch size was also increased to 64. Then the last change was the epochs were doubled from 100 to 200 for more testing.    
![image](https://user-images.githubusercontent.com/89541481/202516073-6ff06ee2-01f7-4513-b686-021bf01d7798.png)      
## Summary
Overall the model does an alright job at being able to predict which applicants will be successfully funded. Though some changes that could be made to improve the model is to perhaps remove readd the SPECIAL_CONSIDERATIONS variable. The reason being is that accuracy did not appear to change by that much without it. Another thing is to test out the different activation combinations. There is also leaky ReLU which appears to be an improvement to ReLU so perhaps it would prove beneficial to the model.
