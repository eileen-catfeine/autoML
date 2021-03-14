# Summary of 46_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.8
- **min_samples_split**: 30
- **max_depth**: 7
- **explain_level**: 1

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

8.7 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.540183 |  nan        |
| auc       | 0.705286 |  nan        |
| f1        | 0.53012  |    0.310375 |
| accuracy  | 0.741228 |    0.56698  |
| precision | 0.607143 |    0.56698  |
| recall    | 1        |    0        |
| mcc       | 0.324171 |    0.379085 |


## Confusion matrix (at threshold=0.56698)
|                     |   Predicted as negative |   Predicted as positive |
|:--------------------|------------------------:|------------------------:|
| Labeled as negative |                     152 |                      11 |
| Labeled as positive |                      48 |                      17 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)

[<< Go back](../README.md)
