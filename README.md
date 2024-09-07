# deep-learning-challenge
Module 21 Challenge

# Analysis Report
## Overview
The purpose of this analysis is to determine the likelihood of a successful applicant endeavor if they receive funding from Alphabet Soup. The independent variables (features) that are analyzed in this program are the affiliation of the program, government classification, use of the program, type of organization, current status, amount of income, and the amount of funding requested.

## Results
The target variable for consideration is the success of the program. This will help the model with determining whether the features measured will be suitable for predicting the success of a new applicant. The feature models I listed above will be the most successful in determining whether an applicant will be successful. The main variable removed were the name of the organization.

After some experimentation, I found that adding a third neural layer bogged down the accuracy of the model to roughly 68%. After testing it, I found that it was best to remove it. I also attempted to bin the Ask-Amt column so that it was less convuluted with rare cases, but this also significantly reduced the accuracy of the model, as well as raised the loss value. I felt it was necessary to remove this binning after several runs with low accuracy. Additionally, I ran multiple compolations of these methods and still found an accuracy under 75%. The most success I had was just raising the number of neural networks in the second hidden layer to 7. This raised it to 75.1% accuracy.

## Summary
I believe that the best way to increase the accuracy of this model would be to increase the number of features present. If the data collected could have more features, it would probably have a higher success.