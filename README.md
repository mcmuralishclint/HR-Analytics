# HR-Analytics

HR analytics is revolutionising the way human resources departments operate, leading to higher efficiency and better results overall. Human resources has been using analytics for years. However, the collection, processing and analysis of data has been largely manual, and given the nature of human resources dynamics and HR KPIs, the approach has been constraining HR. Therefore, it is surprising that HR departments woke up to the utility of machine learning so late in the game. Here is an opportunity to try predictive analytics in identifying the employees most likely to get promoted.

# Overview

1. Missing values in the education field was filled with the mode of the education field with respect to a particular department.
2. Missing values of previous year rating was filled with 0.0
3. Converted the data in the education field into a sequential order. 1 - below secondary, 2 - bachelors and 3 - masters
4. Region field was binned with, regions with workers promoted over 10% and regions with less than 10%
5. Trainings per year was created by dividing number of trainings per year by number of years worked
6. Joining age was added by subtracting the number of years worked from the current age
7. age, joining age and the length of service was binned
8. Total score = number of trainings * average score
9. Categorical variables were label encoded and dummy variables were created
10. Decision tree model was tried by tuning the hyperparameters
11. Cross validation was used on the training data to check for the f1 score for each model
12. LightBGM model proved to work the best. Model was finetuned by applying various values on each variable and an excel sheet was created to identify the suitable model.

 
