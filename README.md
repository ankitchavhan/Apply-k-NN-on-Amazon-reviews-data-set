The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.
Number of reviews: 568,454
Number of users: 256,059
Number of products: 74,258
Timespan: Oct 1999 - Oct 2012
Number of Attributes/Columns in data: 10
Attribute Information:
1. Id
2. ProductId - unique identifier for the product
3. UserId - unqiue identifier for the user
4. ProfileName
5. HelpfulnessNumerator - number of users who found the review helpful
6. HelpfulnessDenominator - number of users who indicated whether they found the review
helpful or not
7. Score - rating between 1 and 5
8. Time - timestamp for the review
9. Summary - brief summary of the review
10. Text - text of the review

Objective :- 
1. There are two tasks of KNN,one is to apply Brute force KNN and other is KD-tree version of KNN. You have to perform both these tasks on all 4 vectorizers. (BOW, TFIDF, AVG-W2V, TFIDF-AVG_W2V)
2. If you have 4GB of RAM then consider 50k points as sample size for brute force algorithm and 20k as sample size for kd-tree algorithm. If your RAM is 8GB then consider a minimum sample size of 100k datapoints for brute force and 20k datapoints for kd-tree algorithm. And if your RAM is less than 4GB then please upgrade your RAM to a minimum of 8GB.
3. You can use sparse matrices for brute force algorithm of KNN.
4. For kd-tree algorithm you have to use dense matrices. Please note that if you pass sparse matrix as input to kd-tree algorithm then by default it will run in brute-force. So please use dense matrices for kd-tree.
5. Use AUC as a metric for hyperparameter tuning.
