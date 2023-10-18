# Report

## Best Model

The best model is DecisionTreeClassifier ( ccp_alpha = 0.001, criterion ='entropy', max_depth = 13, max_features = 'log2', random_state = 2) because it surpasses every metric in evaluation of the test set (Accuracy = 0.97, Precision = 0.95, Recall = 0.97, F1-Score = 0.96) the knn model (Accuracy = 0.94, Precision = 0.93, Recall = 0.90, F1-Score = 0.91).

## Most Valuable Features

The most valuable features based on the DecisionTree model are "cibil_score", "loan_term" and "loan_mount".

## Insights

- The fact that cibil_score is one of the most valuable features suggests that the cibil_score plays a significant role in determining the creditworthiness of applicants. The bank can consider setting a minimum credit score requirement to ensure that applicants have a good credit history and are less likely to default on their loans.

- Due to the fact that loan_term is the second most valuable feature, the bank can also consider adjusting the loan terms to better align with the needs and financial capabilities of their customers.