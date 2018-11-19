# StudentInformationDatabase
Classify whether student fits for a given job using given information in the form of features of the given dataset.
Algorithms Used:
1. Logistic Regression with multinomial multi_class parameter value
2. Decision Trees 
3. Gaussian Naive Bayes

Steps I took: 
I.I tried to understand and familiarize myself with the data set from: 
https://archive.ics.uci.edu/ml/datasets/student+performance 

II. Assumed absolutely essentially details for job requirements: 


Title - Associate Software Developer
Failures = 0
Education - Passed
(i.) Poor fit (label 0) Category parameters:

Health <= 2
Age = 15-16 (both included)
Workday Alcohol Consumption <=2
(ii.) Medium fit (label 1) category parameters:

Health = 3
Age = 17-18 (both included)
Workday Alcohol Consumption = 3
(iii.) Good fit (label 2) category parameters:

Health = 4
Age = 19-20 (both included)
Workday Alcohol Consumption = 4
(iv.) Very Good fit (label 3) category parameters:

Health = 5
Age = 21-22 (both included)
Workday Alcohol Consumption = 5
III. Added a column of marks from an external data set taken from UCI ML repository (Student Performance Dataset) same as mentioned above in step 1 using Excel 
