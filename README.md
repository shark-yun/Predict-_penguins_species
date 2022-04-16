# Predict_penguins_species
Using limited penguins features to predict it's species. 
* We decided to use Culmen Length (mm) and Culmen Depth (mm) as the quantitative features and Island as the qualitative feature.

* We chose this combination of characteristics because we discovered in the Exploratory Analysis Section that Culmen Length & Culmen Depth and Culmen Length & Flipper Length resulted in distinct and separate clusters for each species, meaning it would be easy for the model to distingiush between species using these combinations as the training data. And we using following models (Support Vector Machines, KNeighbor Classifier, Random Forest Classifier) to train the data and make the prediciton and comparing with the actual species.

*** 
Here are the following scores for each model:
Support Vector Machine: **97.1%**
K Neighbors Classifier: **97.1%**
Random Forest Classifier: **98.5%** 

Notice that all of the models performed well each with a score above 97%, and the Random Forest Classifier performed the best with a score of 98.5%.
From our data collection, we would recommend the Random Forest Classifier with the quantitative data being Culmen Length and Culmen Depth, and the qualitative data being island as this achieved the highest score on the test data.
