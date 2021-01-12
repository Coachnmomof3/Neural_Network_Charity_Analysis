# Neural_Network_Charity_Analysis

## Overview

The purpose of this analysis is to display the knowledge gained with machine learning and neural networks. I used the features in the data set with more than 34,000 organizations that have recieved funding from Alphabet Soup over the years. With this information I helped Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results

* Data Preprocessing

   * Target variable is the IS_SUCCESSFUL column.
    
   * Variables that are considered to be the features are listed below:
    'STATUS', 'ASK_AMT', 'IS_SUCCESSFUL', 'APPLICATION_TYPE', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT'. I dropped "USE_CASE_Other","AFFILIATION_Other" columns.
    
   * EIN and NAME are variables that are neither targets nor features
    and were removed from the input data.

* Compiling, Training, and Evaluating the Model
   
   * The Neural Network model has 2 - 3 neurons, 2 - 3 layers and 2 activation functions. The number of neurons, layers, and activation functions were chosen because it was best for binary classifcation problems and nonlinear datasets, tried to accompish higher than 75 target.

   * The target models performance was not acheived.

   * To increase the models performance I changed the number of layers, increased the epochs and remove colomns.

## Results Images
* 1st Run
!()[https://github.com/Coachnmomof3/Neural_Network_Charity_Analysis/blob/main/Images/1st%20Run.png]
* 2nd Run
!()[https://github.com/Coachnmomof3/Neural_Network_Charity_Analysis/blob/main/Images/2nd%20Run.png]
* 3rd Run
!()[https://github.com/Coachnmomof3/Neural_Network_Charity_Analysis/blob/main/Images/3rd%20Run.png]
* 4th Run
!()[https://github.com/Coachnmomof3/Neural_Network_Charity_Analysis/blob/main/Images/Final%20Run%20.7412.png]

## Summary

Even though the models accuracy fluctuated around .741 the overall accuracy score became lower which puzzling considering it was was higher during the run. I think trial and error with the numbers on the layers and epochs can improve this model. A different model could solve this classification problem but if we could understand the data better we could determine how 'IS_SUCCESSFUL' is classified. We would also be successsful if we had a better handel on the different/more models.
