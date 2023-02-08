# Neural_Network_Charity_Analysis
Alphabet Soup Charity Analysis
# Overview
 -Alphabet Soup has a history of funding 34000 organizations in the past. It has been determined that some of the money is slipping through hands and not making its way for the intended cause. This analysis to for the purpose of seeing which organizations are most likely to use the money properly.
## Results
 -There are 12 variables
	-EIN
	-Name
	_Application Type
	-Affiliation
	-Classification
	-Use_Case
	-Organization
	-Status
	-Income_Amt
	-Special_Considerations
	-Ask_Amt
	-Is_Successful
-In the initial model EIN and Name were dropped
-The following are features
-   ‘ NAME’
 'APPLICATION_TYPE',
 'AFFILIATION',
 'CLASSIFICATION',
 'USE_CASE',
 'ORGANIZATION',
 'INCOME_AMT',
 'SPECIAL_CONSIDERATIONS
-EIN and Name are not targets or features and were dropped
-There were 2 neurons, and 13 layers used (8 and 5 hidden)
-The target of 75% accuracy was not achieved
-attempts to achieve the target were to increase the number of epochs from 100 to 200. An attempt to drop only the Name column was also tried.
	-Used, Tensorflow, Keres and Sigmoid

### Summary

	-The original model had 1.2 loss and .53 accuracy
	-The first trial (increasing epochs) with the same result
	-The second trial (adding back “Name” column), program crashed
	-Could not reach the .73 threshold

