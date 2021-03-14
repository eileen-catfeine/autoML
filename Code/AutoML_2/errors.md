## Error for 20_RandomForest_GoldenFeatures

Golden Features not created. Empty scores.
Traceback (most recent call last):
  File "/opt/miniconda3/lib/python3.8/site-packages/supervised/base_automl.py", line 1044, in _fit
    trained = self.train_model(params)
  File "/opt/miniconda3/lib/python3.8/site-packages/supervised/base_automl.py", line 354, in train_model
    mf.train(results_path, model_subpath)
  File "/opt/miniconda3/lib/python3.8/site-packages/supervised/model_framework.py", line 147, in train
    X_train, y_train, sample_weight = self.preprocessings[
  File "/opt/miniconda3/lib/python3.8/site-packages/supervised/preprocessing/preprocessing.py", line 189, in fit_and_transform
    self._golden_features.fit(X_train[numeric_cols], y_train)
  File "/opt/miniconda3/lib/python3.8/site-packages/supervised/preprocessing/goldenfeatures_transformer.py", line 165, in fit
    raise AutoMLException("Golden Features not created. Empty scores.")
supervised.exceptions.AutoMLException: Golden Features not created. Empty scores.


Please set a GitHub issue with above error message at: https://github.com/mljar/mljar-supervised/issues/new

## Error for 4_Default_CatBoost_GoldenFeatures

Golden Features not created due to error (please check errors.md). Golden Features not created. Empty scores. Input data shape: (182, 1), (182,)
Traceback (most recent call last):
  File "/opt/miniconda3/lib/python3.8/site-packages/supervised/base_automl.py", line 1044, in _fit
    trained = self.train_model(params)
  File "/opt/miniconda3/lib/python3.8/site-packages/supervised/base_automl.py", line 354, in train_model
    mf.train(results_path, model_subpath)
  File "/opt/miniconda3/lib/python3.8/site-packages/supervised/model_framework.py", line 147, in train
    X_train, y_train, sample_weight = self.preprocessings[
  File "/opt/miniconda3/lib/python3.8/site-packages/supervised/preprocessing/preprocessing.py", line 189, in fit_and_transform
    self._golden_features.fit(X_train[numeric_cols], y_train)
  File "/opt/miniconda3/lib/python3.8/site-packages/supervised/preprocessing/goldenfeatures_transformer.py", line 132, in fit
    raise AutoMLException(
supervised.exceptions.AutoMLException: Golden Features not created due to error (please check errors.md). Golden Features not created. Empty scores. Input data shape: (182, 1), (182,)


Please set a GitHub issue with above error message at: https://github.com/mljar/mljar-supervised/issues/new

## Error for 16_CatBoost_GoldenFeatures

Golden Features not created due to error (please check errors.md). Golden Features not created. Empty scores. Input data shape: (182, 1), (182,)
Traceback (most recent call last):
  File "/opt/miniconda3/lib/python3.8/site-packages/supervised/base_automl.py", line 1044, in _fit
    trained = self.train_model(params)
  File "/opt/miniconda3/lib/python3.8/site-packages/supervised/base_automl.py", line 354, in train_model
    mf.train(results_path, model_subpath)
  File "/opt/miniconda3/lib/python3.8/site-packages/supervised/model_framework.py", line 147, in train
    X_train, y_train, sample_weight = self.preprocessings[
  File "/opt/miniconda3/lib/python3.8/site-packages/supervised/preprocessing/preprocessing.py", line 189, in fit_and_transform
    self._golden_features.fit(X_train[numeric_cols], y_train)
  File "/opt/miniconda3/lib/python3.8/site-packages/supervised/preprocessing/goldenfeatures_transformer.py", line 132, in fit
    raise AutoMLException(
supervised.exceptions.AutoMLException: Golden Features not created due to error (please check errors.md). Golden Features not created. Empty scores. Input data shape: (182, 1), (182,)


Please set a GitHub issue with above error message at: https://github.com/mljar/mljar-supervised/issues/new

