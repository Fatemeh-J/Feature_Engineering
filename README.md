# Feature_Engineering
In this project we will explore supervised methods for feature selection, including "Filter", "Wrapper", and "Embedded" methods. You can download the dataset from [this link](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic).
Feature selection is an important aspect of each data sceince project which involves picking the set of features that are most relevant to the target variable. This can be helpful for reducing the complexity of our model. Feature selection becomes more impactful in production, especially when handling terabytes of data or serving millions of requests.
At the end, we will compare the performance of each feature selection technique regarding the following evaluation metrics: accuracy, roc, precision, recall and f1-score.

### Filter Methods
- Correlation with the target variable
- Correlation with other features
- Univariate Selection

 ### Wrapper Methods
- Recursive Feature Elimination
- Forward Elimination
- Backward Elimination

### Embedded Methods
- Feature Importances
- L1 Regularization
