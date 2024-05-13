# credit-risk-classification aka Module 20 Challenge

Module 20 Challenge uses Python and supervised learning to predict if loans applications will be approved. 

## Installation

use github repo with terminal of your choice

## Usage

Module 20 Challenge uses Python and supervised learning to predict if loans applications will be approved. 

## Sources

class materials and lectures

## License

None

## Analysis

Overview of the Analysis
The analysis that I did for the Module 20 Challenge uses credit report data to predict if loans would be approved or not using various pieces of data such debt-to-income ration, borrower income, number of accounts they have open, derogatory marks on their credit report, etc. That was then compared to the actual loan application results. 

This was accmoplished by first reading in the data from the csv file and creating a dataframe with it. Then I separated the dependent variable "y" from the other variables which are independent and are all under "X". In this case y was the "loan status" column, and the X's were loan size, interest rate, borrower income, debt-to-income ration, number of accounts,
derogatory marks, and total debt. Next I split the data in the training and testing datasets. Then I did logistic regression and fit the model using the training data. I then did predictions on the testing data labels, and created a new dataframe with the results that showed the predictions compared to the actual loan application results. Lastly, I did a confusion matrix and printed it using target names.

Results
The confusion matrix shows that credit risk classification was highly accurate and highly precise. 

Summary
This machine learning model was a big success and thus it would be recommended by anyone who is into this kind of thing. Likely performance would depend on the problem that one is trying to solve.
