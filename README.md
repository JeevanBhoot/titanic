# KaggleTitanic
My Jupyter Notebook for working through the Titanic dataset on Kaggle.

Final submission achieved an accuracy of 78.5% using a random forest classifier with the following hyper-parameters:
n_estimators: 138,
min_samples_split: 8,
min_samples_leaf: 5,
max_features: auto,
max_depth: 199, and
bootstrap: False,
which were found using a randomised search.

The final submission used the following engineered features:
Family size,
Age range, and
Title.
