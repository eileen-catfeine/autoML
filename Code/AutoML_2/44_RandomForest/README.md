# Summary of 44_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.9
- **min_samples_split**: 30
- **max_depth**: 3
- **explain_level**: 1

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

5.0 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.522894 |  nan        |
| auc       | 0.728834 |  nan        |
| f1        | 0.573529 |    0.373878 |
| accuracy  | 0.754386 |    0.632621 |
| precision | 1        |    0.632621 |
| recall    | 1        |    0        |
| mcc       | 0.393559 |    0.373878 |


## Confusion matrix (at threshold=0.632621)
|                     |   Predicted as negative |   Predicted as positive |
|:--------------------|------------------------:|------------------------:|
| Labeled as negative |                     163 |                       0 |
| Labeled as positive |                      56 |                       9 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)

[<< Go back](../README.md)
