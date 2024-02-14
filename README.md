# Feature_Engineering
Feature selection is an important aspect of each data sceince project which involves picking the set of features that are most relevant to the target variable. It can be helpful for reducing the complexity of our model. Feature selection becomes more impactful in production, especially when handling terabytes of data or serving millions of requests. There are many different methods for feature selection, however, in this project we have a focus on supervised methods including "Filter", "Wrapper", and "Embedded" methods.

We compare the performance of each feature selection technique regarding the following evaluation metrics: accuracy, roc, precision, recall and f1-score.
The dataset is available at [this link](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic).

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
