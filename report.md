# Deep-Learning-Project

## Overview 
This project aims to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup. The major focus of this assignment is to practice working with machine learning models and optimizing them. The goal is to get this model above 75% accurate.

## Results: 
  ### Data Preprocessing
  -The target variable is 'IS_SUCCESSFUL'
  -The features are everything else other than the target that was used in the model.
  -'names' and 'EIN' were removed because they are not useful

  ### Compiling, Training, and Evaluating the Model
  When creating the first model, I went with 2 relu hidden layers and a sigmoid ouput. My two hidden layers had 90 and 40 respectively. The second model was set up very similar to the first except I changed from relu activation to a tanh activation, which improved the model. Since tanh improved the accuracy of the model, I decided to try adding another tanh layer which decreased the accuracy by 0.0002. The final attempt, I increased the number of epochs from 100 to 150, which didnt change the accuracy at all. I was unable to reach the goal of 75%. The highest accuracy I achieved was .7299 with the second model. 
  
## Summary
  Overall I was unable to achieve the goal of an accuracy of 75%. If I were to continue optimizing this model I would try looking for more outliers within the data. I would also make more adjustments to my second model which got the highest accuracy using two tanh hidden layers.
