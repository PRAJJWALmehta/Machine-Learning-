
- we split the data into K folds or subsets
- one chunk of data is used as test data for evaluation and the remaining part of the data us used for training
- each time, a different chunk will be used as the test data
- after training data for each iteration or fold we calculate the mean accuracy

### Advantages

- better alternative for train test split when the dataset is small
- better for Multiclass Classification problems
- reliable
- useful for model selection

### documentation

[sklearn.model_selection.KFold](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.KFold.html)

[sklearn.model_selection.cross_val_score](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_val_score.html)
