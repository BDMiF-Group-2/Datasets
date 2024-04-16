# Datasets Description

- train: train set with 92 features. One feature with zero variance and three features perfectly correlated with other three were removed from the original data.
- test: train set with 92 features. One feature with zero variance and three features perfectly correlated with other three were removed from the original data.
- train_bal: balanced train set with the same 92 features of the based train set.
- train_feat_sel: train set after feature selection based on multicollinearity testing (VIF values). Only 52 features remaining.
- train_bal_feat_sel: subset of the balanced train set (train_bal) with only the 52 features from the feature selection.
