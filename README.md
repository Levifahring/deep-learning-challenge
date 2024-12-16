# deep-learning-challenge

The nature of this analysis is to determine whether or not an organization will be successful if funded by Alphabet Soup. 

The features included in this analysis is as follows:
![image](https://github.com/user-attachments/assets/dfcda4a6-6196-46ff-99c0-42a36ea7969f)


APPLICATION_TYPE
AFFILIATION	
CLASSIFICATION	
USE_CASE	
ORGANIZATION	
STATUS	
INCOME_AMT	
SPECIAL_CONSIDERATIONS	
ASK_AMT	

The target variable is as follows:

IS_SUCCESSFUL


The unneeded variables that were removed from the feature list due to being unneeded is as follows:

EIN 
NAME


The following is layers I added to the model:



I chose to add 150 neurons to the first layer, 100 to the second, and 100 to the third. I was hoping that this would be an optimal amount of neurons to get the accuracy of the model above 75%. I went with the RELU function for the first three layers to help alleviate the vanishing gradient problem. The non-linearity of the function helps it to learn complex data. 

On the output layer I went with a sigmoid function because we are trying to determine a binary result. 

I was unable to achieve the desired target of 75% efficiency. I spent a long time trying different things but seemed only to lower the score. I tried adding more neurons, layers, and different activation functions. I changed cutoff values, dropped other columns, and switched which optimization I was using. 

In summary, I was not able to optimize this model to the desired result. If I had more time to learn about how each part worked in its entirety I believe I would have been more successful. 

